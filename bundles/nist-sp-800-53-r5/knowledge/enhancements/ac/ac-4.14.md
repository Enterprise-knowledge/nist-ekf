---
type: control_enhancement
title: AC-4.14 - Security or Privacy Policy Filter Constraints
description: 'When transferring information between different security domains, implement {{ insert: param, ac-4.14_prm_1
  }} requiring fully enumerated formats that restrict data structure and content.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-4.md
  relation: part_of
  description: AC-4.14 - Security or Privacy Policy Filter Constraints is part of its parent SP 800-53 structure.
- name: AC-4 - Information Flow Enforcement
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-4.md
  relation: enhances
  description: AC-4.14 enhances base control AC-4.
nist_id: AC-4.14
sort_id: ac-04.14
implementation_level: system
parameter_ids:
- ac-4.14_prm_1
- ac-04.14_odp.01
- ac-04.14_odp.02
reference_links:
- '#ac-4'
---

# Summary

When transferring information between different security domains, implement {{ insert: param, ac-4.14_prm_1 }} requiring fully enumerated formats that restrict data structure and content.

# Statement

When transferring information between different security domains, implement {{ insert: param, ac-4.14_prm_1 }} requiring fully enumerated formats that restrict data structure and content.

# Guidance

Data structure and content restrictions reduce the range of potential malicious or unsanctioned content in cross-domain transactions. Security or privacy policy filters that restrict data structures include restricting file sizes and field lengths. Data content policy filters include encoding formats for character sets, restricting character data fields to only contain alpha-numeric characters, prohibiting special characters, and validating schema structures.

# Parameters

- `ac-4.14_prm_1`
- `ac-04.14_odp.01`
- `ac-04.14_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
