---
type: control_enhancement
title: AC-4.1 - Object Security and Privacy Attributes
description: 'Use {{ insert: param, ac-4.1_prm_1 }} associated with {{ insert: param, ac-4.1_prm_2 }} to enforce
  {{ insert: param, ac-04.01_odp.09 }} as a basis for flow control decisions.'
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
  description: AC-4.1 - Object Security and Privacy Attributes is part of its parent SP 800-53 structure.
- name: AC-4 - Information Flow Enforcement
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-4.md
  relation: enhances
  description: AC-4.1 enhances base control AC-4.
nist_id: AC-4.1
sort_id: ac-04.01
implementation_level: system
parameter_ids:
- ac-4.1_prm_1
- ac-4.1_prm_2
- ac-04.01_odp.01
- ac-04.01_odp.02
- ac-04.01_odp.03
- ac-04.01_odp.04
- ac-04.01_odp.05
- ac-04.01_odp.06
- ac-04.01_odp.07
- ac-04.01_odp.08
- ac-04.01_odp.09
reference_links:
- '#ac-4'
---

# Summary

Use {{ insert: param, ac-4.1_prm_1 }} associated with {{ insert: param, ac-4.1_prm_2 }} to enforce {{ insert: param, ac-04.01_odp.09 }} as a basis for flow control decisions.

# Statement

Use {{ insert: param, ac-4.1_prm_1 }} associated with {{ insert: param, ac-4.1_prm_2 }} to enforce {{ insert: param, ac-04.01_odp.09 }} as a basis for flow control decisions.

# Guidance

Information flow enforcement mechanisms compare security and privacy attributes associated with information (i.e., data content and structure) and source and destination objects and respond appropriately when the enforcement mechanisms encounter information flows not explicitly allowed by information flow policies. For example, an information object labeled Secret would be allowed to flow to a destination object labeled Secret, but an information object labeled Top Secret would not be allowed to flow to a destination object labeled Secret. A dataset of personally identifiable information may be tagged with restrictions against combining with other types of datasets and, thus, would not be allowed to flow to the restricted dataset. Security and privacy attributes can also include source and destination addresses employed in traffic filter firewalls. Flow enforcement using explicit security or privacy attributes can be used, for example, to control the release of certain types of information.

# Parameters

- `ac-4.1_prm_1`
- `ac-4.1_prm_2`
- `ac-04.01_odp.01`
- `ac-04.01_odp.02`
- `ac-04.01_odp.03`
- `ac-04.01_odp.04`
- `ac-04.01_odp.05`
- `ac-04.01_odp.06`
- `ac-04.01_odp.07`
- `ac-04.01_odp.08`
- `ac-04.01_odp.09`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
