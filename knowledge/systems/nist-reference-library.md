---
type: system
title: NIST Reference Library
description: Source system for local NIST PDFs and official NIST machine-readable exports used by the EKF demo.
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: nist-governance
system: nist-reference-library
tags:
- nist
- source
- reference-library
- oscal
- csf
- ai-rmf
confidence: high
review:
  status: agent-generated
  reviewed_by: EKF generation workflow
  reviewed_at: '2026-06-22T00:00:00Z'
sources:
- name: NIST CSF 2.0 PDF
  path: /source/NIST.CSWP.29.pdf
  kind: pdf
  description: NIST Cybersecurity Framework 2.0 publication.
- name: NIST AI RMF 1.0 PDF
  path: /source/NIST.AI.100-1.pdf
  kind: pdf
  description: NIST AI RMF 1.0 publication.
- name: NIST SP 800-53 Rev. 5 PDF
  path: /source/NIST.SP.800-53r5.pdf
  kind: pdf
  description: NIST SP 800-53 Rev. 5 publication.
- name: NIST OSCAL SP 800-53 catalog
  path: /artifacts/data/NIST_SP-800-53_rev5_catalog.json
  kind: oscal
  description: Downloaded NIST OSCAL catalog used as structured supplemental data.
- name: NIST AI RMF Playbook JSON
  path: /artifacts/data/ai-rmf-playbook.json
  kind: json
  description: Downloaded NIST AI RMF Playbook JSON used as structured supplemental data.
- name: NIST CSF Reference Tool export
  path: /artifacts/data/csf-2.0-export.xlsx
  kind: xlsx
  description: Downloaded CSF Reference Tool export used for implementation examples.
related:
- name: NIST Governance Corpus
  path: /knowledge/domains/nist-governance-corpus.md
  relation: supports
  description: The reference library supplies source material for the corpus.
---

# Summary

The NIST Reference Library is the source-system concept for this demo. It includes immutable local PDFs plus generated markdown and official NIST structured exports.

# Source Notes

The generated EKF concepts cite the local PDFs as requested source material. NIST machine-readable exports are preserved under `/artifacts/data/` when they provide more precise structure for controls, implementation examples, or playbook entries.

# Citations

[1] [Source manifest](/source/ekf-source.yml)
