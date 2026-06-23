# Contributing To The NIST EKF Demo

Thanks for helping improve the NIST EKF demo.

This repository is a demonstration bundle for Enterprise Knowledge Format. Contributions should keep the demo focused on public NIST material, source provenance, generated artifacts, and typed graph relationships.

## Useful Contributions

- Improve generated concept descriptions while preserving source provenance.
- Improve the generation script in `scripts/generate_nist_ekf.py`.
- Improve the graph artifact or generated graph data.
- Fix validation issues reported by the EKF validator.
- Improve README guidance for people evaluating EKF.

## Source Material Rules

Only public or synthetic source material should be added. Do not contribute credentials, private keys, access tokens, customer data, confidential internal documents, or proprietary source material.

Original source files belong under `source/`. Generated markdown renderings belong under `artifacts/markdown/`. Curated EKF concepts belong under `knowledge/` or nested bundle `knowledge/` trees.

## Validation

Run these checks before opening a pull request:

```sh
uv run python -m py_compile scripts/generate_nist_ekf.py
uv run --with pyyaml python .agents/skills/ekf-bootstrap/scripts/validate_ekf.py .
uv run --with pyyaml python .agents/skills/ekf-bootstrap/scripts/parse_ekf_graph.py . \
  --output /tmp/nist-ekf-graph.json
```

Optional text checks:

```sh
rg -n "[T]ODO|[T]BD|[F]IXME" README.md index.md knowledge bundles meta scripts .agents/skills/ekf-bootstrap
```

## License

By contributing, you agree that your contribution will be licensed under the Apache License 2.0.
