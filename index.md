---
type: bundle
title: NIST Governance EKF Demo
description: Enterprise Knowledge Format demo bundle for NIST cybersecurity, AI risk, and security control publications.
ekf_version: '0.1'
bundle:
  id: nist-governance-ekf-demo
  kind: root
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
---

# NIST Governance EKF Demo

This EKF bundle is a publication-backed knowledge base for NIST governance material. It keeps local PDFs as source material, generated full-text markdown as artifacts, curated concepts under `knowledge/`, and publication-specific nested bundles under `bundles/`.

## Knowledge

- [Knowledge](knowledge/) - Cross-publication concepts and discovery indexes.

## Sources

- [Sources](source/) - Local NIST PDF source files and source manifest.

## Artifacts

- [Artifacts](artifacts/) - Generated markdown extractions, NIST data exports, graph JSON, and HTML graph demo.

## Nested Bundles

- [NIST Cybersecurity Framework 2.0](bundles/nist-csf-2/) - CSF 2.0 Functions, Categories, Subcategories, Profiles, Tiers, and Implementation Examples.
- [NIST AI RMF 1.0](bundles/nist-ai-rmf-1/) - AI RMF Core Functions, Categories, Subcategories, Playbook content, trustworthiness characteristics, and profiles.
- [NIST SP 800-53 Rev. 5](bundles/nist-sp-800-53-r5/) - Security and privacy control families, controls, control enhancements, publication sections, and glossary/acronym material.
