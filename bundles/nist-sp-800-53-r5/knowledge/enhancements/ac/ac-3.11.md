---
type: control_enhancement
title: AC-3.11 - Restrict Access to Specific Information Types
description: 'Restrict access to data repositories containing {{ insert: param, ac-03.11_odp }}.'
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
- ac
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-3.md
  relation: part_of
  description: AC-3.11 - Restrict Access to Specific Information Types is part of its parent SP 800-53 structure.
- name: AC-3 - Access Enforcement
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-3.md
  relation: enhances
  description: AC-3.11 enhances base control AC-3.
nist_id: AC-3.11
sort_id: ac-03.11
implementation_level: system
parameter_ids:
- ac-03.11_odp
reference_links:
- '#ac-3'
- '#cm-8'
- '#cm-12'
- '#cm-13'
- '#pm-5'
---

# Summary

Restrict access to data repositories containing {{ insert: param, ac-03.11_odp }}.

# Statement

Restrict access to data repositories containing {{ insert: param, ac-03.11_odp }}.

# Guidance

Restricting access to specific information is intended to provide flexibility regarding access control of specific information types within a system. For example, role-based access could be employed to allow access to only a specific type of personally identifiable information within a database rather than allowing access to the database in its entirety. Other examples include restricting access to cryptographic keys, authentication information, and selected system information.

# Parameters

- `ac-03.11_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
