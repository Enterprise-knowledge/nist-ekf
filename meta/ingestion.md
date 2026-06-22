# NIST Governance EKF Demo Ingestion

This bundle is generated from local PDFs in `/source/` plus official NIST machine-readable exports downloaded into `/artifacts/data/`.

## Workflow

1. Extract every PDF page into `/artifacts/markdown/documents/`.
2. Download CSF Reference Tool export, AI RMF Playbook JSON, and SP 800-53 OSCAL catalog into `/artifacts/data/`.
3. Generate curated EKF concept markdown under root `knowledge/` and publication-specific nested bundles.
4. Validate with `.agents/skills/ekf-bootstrap/scripts/validate_ekf.py`.
5. Parse graph JSON with `.agents/skills/ekf-bootstrap/scripts/parse_ekf_graph.py`.
6. Fill `.agents/skills/ekf-bootstrap/assets/graph-template.html` into `/artifacts/html/knowledge-graph/index.html`.
