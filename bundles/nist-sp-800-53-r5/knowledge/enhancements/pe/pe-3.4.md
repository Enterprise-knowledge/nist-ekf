---
type: control_enhancement
title: PE-3.4 - Lockable Casings
description: 'Use lockable physical casings to protect {{ insert: param, pe-03.04_odp }} from unauthorized physical
  access.'
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
- pe
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-3.md
  relation: part_of
  description: PE-3.4 - Lockable Casings is part of its parent SP 800-53 structure.
- name: PE-3 - Physical Access Control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-3.md
  relation: enhances
  description: PE-3.4 enhances base control PE-3.
nist_id: PE-3.4
sort_id: pe-03.04
implementation_level: organization
parameter_ids:
- pe-03.04_odp
reference_links:
- '#pe-3'
---

# Summary

Use lockable physical casings to protect {{ insert: param, pe-03.04_odp }} from unauthorized physical access.

# Statement

Use lockable physical casings to protect {{ insert: param, pe-03.04_odp }} from unauthorized physical access.

# Guidance

The greatest risk from the use of portable devices—such as smart phones, tablets, and notebook computers—is theft. Organizations can employ lockable, physical casings to reduce or eliminate the risk of equipment theft. Such casings come in a variety of sizes, from units that protect a single notebook computer to full cabinets that can protect multiple servers, computers, and peripherals. Lockable physical casings can be used in conjunction with cable locks or lockdown plates to prevent the theft of the locked casing containing the computer equipment.

# Parameters

- `pe-03.04_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
