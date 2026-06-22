---
type: domain
title: NIST Governance Corpus
description: Cross-publication domain connecting cybersecurity risk, AI risk, and security and privacy controls.
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: nist-governance
system: nist-reference-library
tags:
- nist
- governance
- cybersecurity
- ai-risk
- controls
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
related:
- name: NIST Cybersecurity Framework 2.0
  path: /bundles/nist-csf-2/knowledge/publication.md
  relation: contains
  description: The corpus includes CSF 2.0 as a cybersecurity risk management framework.
- name: NIST AI RMF 1.0
  path: /bundles/nist-ai-rmf-1/knowledge/publication.md
  relation: contains
  description: The corpus includes AI RMF 1.0 as an AI risk management framework.
- name: NIST SP 800-53 Rev. 5
  path: /bundles/nist-sp-800-53-r5/knowledge/publication.md
  relation: contains
  description: The corpus includes SP 800-53 Rev. 5 as a control catalog.
---

# Summary

The NIST Governance Corpus brings together three complementary NIST publications: CSF 2.0 for cybersecurity risk outcomes, AI RMF 1.0 for trustworthy AI risk management, and SP 800-53 Rev. 5 for security and privacy controls.

# Scope

This root concept is intentionally cross-publication. Detailed concepts live in nested bundles so each publication remains independently navigable and maintainable.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[3] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
