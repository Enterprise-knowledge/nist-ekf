---
type: control_enhancement
title: SA-8.29 - Repeatable and Documented Procedures
description: 'Implement the security design principle of repeatable and documented procedures in {{ insert: param,
  sa-08.29_odp }}.'
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control-enhancement
- sa
confidence: high
review:
  status: agent-generated
  reviewed_by: EKF generation workflow
  reviewed_at: '2026-06-22T00:00:00Z'
sources:
- name: NIST SP 800-53 Rev. 5 PDF
  path: /source/NIST.SP.800-53r5.pdf
  kind: pdf
  description: Local source PDF for SP 800-53 Rev. 5.
- name: NIST OSCAL SP 800-53 catalog
  path: /artifacts/data/NIST_SP-800-53_rev5_catalog.json
  kind: oscal
  description: Official NIST OSCAL catalog used as structured supplemental data for controls and enhancements.
related:
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-8.md
  relation: part_of
  description: SA-8.29 - Repeatable and Documented Procedures is part of its parent SP 800-53 structure.
- name: SA-8 - Security and Privacy Engineering Principles
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-8.md
  relation: enhances
  description: SA-8.29 enhances base control SA-8.
nist_id: SA-8.29
sort_id: sa-08.29
implementation_level: organization
parameter_ids:
- sa-08.29_odp
reference_links:
- '#sa-8'
- '#cm-1'
- '#sa-1'
- '#sa-10'
- '#sa-11'
- '#sa-15'
- '#sa-17'
- '#sc-1'
- '#si-1'
---

# Summary

Implement the security design principle of repeatable and documented procedures in {{ insert: param, sa-08.29_odp }}.

# Statement

Implement the security design principle of repeatable and documented procedures in {{ insert: param, sa-08.29_odp }}.

# Guidance

The principle of repeatable and documented procedures states that the techniques and methods employed to construct a system component permit the same component to be completely and correctly reconstructed at a later time. Repeatable and documented procedures support the development of a component that is identical to the component created earlier, which may be in widespread use. In the case of other system artifacts (e.g., documentation and testing results), repeatability supports consistency and the ability to inspect the artifacts. Repeatable and documented procedures can be introduced at various stages within the system development life cycle and contribute to the ability to evaluate assurance claims for the system. Examples include systematic procedures for code development and review, procedures for the configuration management of development tools and system artifacts, and procedures for system delivery.

# Parameters

- `sa-08.29_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
