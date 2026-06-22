# NIST Governance EKF Demo Conventions

## Tags

Use lowercase kebab-case tags. Preserve NIST identifiers in `nist_id` frontmatter and in titles.

## Generated Concepts

The generated publication bundles are produced by `scripts/generate_nist_ekf.py`. Manual edits should either update the generator or be documented in `log.md`.

## Search

Prefer `rg` for text discovery and fall back to `grep -R --line-number` when `rg` is unavailable.
