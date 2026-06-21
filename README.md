# NIST EKF

This repository is a starter Enterprise Knowledge Format (EKF) knowledge base for a NIST governance corpus.

It was bootstrapped with the `ekf-bootstrap` skill and currently stops at the source-ingestion stage: the NIST PDF sources are stored under `source/`, while curated EKF concepts and generated markdown artifacts have not been created yet.

## Sources

- `source/NIST.CSWP.29.pdf` - NIST Cybersecurity Framework (CSF) 2.0
- `source/NIST.AI.100-1.pdf` - Artificial Intelligence Risk Management Framework (AI RMF) 1.0
- `source/NIST.SP.800-53r5.pdf` - Security and Privacy Controls for Information Systems and Organizations

## EKF Standard and Skill

The Enterprise Knowledge Format standard and the canonical `ekf-bootstrap` skill are maintained in the parent repository:

https://github.com/Enterprise-knowledge/enterprise-knowledge-format

This demo repository also installs the skill locally with `npx skills`, so agents can use the same bootstrap, validation, parsing, and graph helper scripts from:

```text
.agents/skills/ekf-bootstrap/
```

To restore the project skill install from the lock file, run:

```sh
npx skills experimental_install
```

To validate this EKF bundle:

```sh
uv run --with pyyaml python .agents/skills/ekf-bootstrap/scripts/validate_ekf.py .
```
