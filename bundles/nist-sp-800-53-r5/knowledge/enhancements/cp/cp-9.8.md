---
type: control_enhancement
title: CP-9.8 - Cryptographic Protection
description: 'Implement cryptographic mechanisms to prevent unauthorized disclosure and modification of {{ insert:
  param, cp-09.08_odp }}.'
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
- cp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-9.md
  relation: part_of
  description: CP-9.8 - Cryptographic Protection is part of its parent SP 800-53 structure.
- name: CP-9 - System Backup
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-9.md
  relation: enhances
  description: CP-9.8 enhances base control CP-9.
nist_id: CP-9.8
sort_id: cp-09.08
implementation_level: organization
parameter_ids:
- cp-09.08_odp
reference_links:
- '#cp-9'
- '#sc-12'
- '#sc-13'
- '#sc-28'
---

# Summary

Implement cryptographic mechanisms to prevent unauthorized disclosure and modification of {{ insert: param, cp-09.08_odp }}.

# Statement

Implement cryptographic mechanisms to prevent unauthorized disclosure and modification of {{ insert: param, cp-09.08_odp }}.

# Guidance

The selection of cryptographic mechanisms is based on the need to protect the confidentiality and integrity of backup information. The strength of mechanisms selected is commensurate with the security category or classification of the information. Cryptographic protection applies to system backup information in storage at both primary and alternate locations. Organizations that implement cryptographic mechanisms to protect information at rest also consider cryptographic key management solutions.

# Parameters

- `cp-09.08_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
