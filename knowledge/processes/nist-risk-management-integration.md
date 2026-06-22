---
type: business_process
title: NIST Risk Management Integration
description: Integration concept explaining how CSF outcomes, AI RMF outcomes, and SP 800-53 controls can be traversed
  together.
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: nist-governance
system: nist-reference-library
tags:
- nist
- risk-management
- integration
- framework
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
- name: CSF Core
  path: /bundles/nist-csf-2/knowledge/core/csf-core.md
  relation: uses
  description: CSF Core outcomes structure cybersecurity risk management.
- name: AI RMF Core
  path: /bundles/nist-ai-rmf-1/knowledge/core/ai-rmf-core.md
  relation: uses
  description: AI RMF Core outcomes structure AI risk management.
- name: SP 800-53 Control Catalog
  path: /bundles/nist-sp-800-53-r5/knowledge/publication.md
  relation: supports
  description: SP 800-53 controls provide selectable safeguards and assessment-oriented detail.
---

# Summary

CSF 2.0, AI RMF 1.0, and SP 800-53 Rev. 5 occupy different layers of risk management. CSF and AI RMF organize desired outcomes and lifecycle practices; SP 800-53 provides a catalog of security and privacy controls that can support implementation and assessment.

# Behavior

The graph uses typed relations to move from publications to framework cores, functions, categories, subcategories, control families, controls, and enhancements. It does not claim one-to-one mappings unless a concept explicitly cites a mapping source.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[3] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
