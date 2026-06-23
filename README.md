# NIST EKF Demo

This repository is a public Enterprise Knowledge Format (EKF) demo built from NIST governance material.

It shows how EKF separates source material, curated markdown knowledge, generated artifacts, and typed graph relationships while keeping the whole knowledge base inspectable with ordinary repo tools.

![NIST EKF knowledge graph demo](assets/nist-ekf-knowledge-graph.png)

## What This Demo Contains

- **1,478 EKF concepts** under `knowledge/` and nested bundle `knowledge/` trees.
- **3,806 typed relationships** declared in `related` YAML frontmatter.
- **4 EKF bundles**: one root governance corpus and three nested publication bundles.
- **3 public NIST source PDFs** under `source/`.
- **Generated markdown extractions** under `artifacts/markdown/`.
- **Official NIST machine-readable exports** under `artifacts/data/`.
- **Graph JSON** under `artifacts/graph/`.
- **Static HTML graph artifact** under `artifacts/html/knowledge-graph/`.

## Source Corpus

The demo uses public NIST material:

- `source/NIST.CSWP.29.pdf` - NIST Cybersecurity Framework (CSF) 2.0
- `source/NIST.AI.100-1.pdf` - Artificial Intelligence Risk Management Framework (AI RMF) 1.0
- `source/NIST.SP.800-53r5.pdf` - Security and Privacy Controls for Information Systems and Organizations

The source manifest is [source/ekf-source.yml](source/ekf-source.yml).

## Bundle Structure

- [index.md](index.md) - Root EKF bundle discovery index.
- [knowledge/](knowledge/) - Cross-publication concepts and routing concepts.
- [bundles/nist-csf-2/](bundles/nist-csf-2/) - CSF 2.0 functions, categories, subcategories, profiles, tiers, and examples.
- [bundles/nist-ai-rmf-1/](bundles/nist-ai-rmf-1/) - AI RMF functions, categories, subcategories, playbook content, trustworthiness characteristics, and profiles.
- [bundles/nist-sp-800-53-r5/](bundles/nist-sp-800-53-r5/) - SP 800-53 control families, controls, enhancements, publication sections, glossary, and acronyms.
- [artifacts/html/knowledge-graph/index.html](artifacts/html/knowledge-graph/index.html) - Browser-readable graph view.

## Why This Demo Exists

Enterprise governance knowledge is usually scattered across PDFs, spreadsheets, taxonomies, control catalogs, implementation notes, and internal wikis. This demo turns public governance sources into an EKF bundle so people and agents can:

- discover the corpus through short indexes and descriptions,
- trace curated concepts back to source publications and generated artifacts,
- traverse typed relationships without parsing prose,
- inspect generated graph data without a graph database,
- keep canonical explanations in markdown instead of generated HTML.

## Open The Graph

After checking out this repository, open the graph artifact directly in a browser:

```text
artifacts/html/knowledge-graph/index.html
```

No build step, database, local server, or hosted search service is required.

## Regenerate The Demo

The generation script is [scripts/generate_nist_ekf.py](scripts/generate_nist_ekf.py). It reads local source PDFs, downloads public NIST machine-readable exports, writes EKF concepts and artifacts, validates the bundle, parses the graph, and builds the static graph HTML.

Install dependencies and run:

```sh
uv sync
uv run python scripts/generate_nist_ekf.py
```

The script uses the locally installed `ekf-bootstrap` skill under `.agents/skills/ekf-bootstrap/`.

To restore the project skill install from the lock file:

```sh
npx skills experimental_install
```

## Validate

Validate this EKF bundle:

```sh
uv run --with pyyaml python .agents/skills/ekf-bootstrap/scripts/validate_ekf.py .
```

Parse the graph:

```sh
uv run --with pyyaml python .agents/skills/ekf-bootstrap/scripts/parse_ekf_graph.py . \
  --output artifacts/graph/graph.json
```

## EKF Standard

The Enterprise Knowledge Format standard and canonical bootstrap skill are maintained at:

https://github.com/Enterprise-knowledge/enterprise-knowledge-format

## Status

Demo v0.1. The bundle is suitable for exploring EKF structure, graph traversal, source provenance, and generated artifacts. It is not an official NIST product.

## License

This demo repository is licensed under the [Apache License 2.0](LICENSE). NIST publications and NIST data exports are included as public source material and retain their original attribution and publication context.
