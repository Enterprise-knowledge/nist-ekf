---
type: control
title: PM-5 - System Inventory
description: 'Develop and update {{ insert: param, pm-05_odp }} an inventory of organizational systems.'
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control
- pm
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/pm.md
  relation: part_of
  description: PM-5 - System Inventory is part of its parent SP 800-53 structure.
- name: PM-5.1 - Inventory of Personally Identifiable Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pm/pm-5.1.md
  relation: has_enhancement
  description: PM-5 has enhancement PM-5.1.
nist_id: PM-5
sort_id: pm-05
implementation_level: organization
parameter_ids:
- pm-05_odp
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#98d415ca-7281-4064-9931-0c366637e324'
---

# Summary

Develop and update {{ insert: param, pm-05_odp }} an inventory of organizational systems.

# Statement

Develop and update {{ insert: param, pm-05_odp }} an inventory of organizational systems.

# Guidance

[OMB A-130](#27847491-5ce1-4f6a-a1e4-9e483782f0ef) provides guidance on developing systems inventories and associated reporting requirements. System inventory refers to an organization-wide inventory of systems, not system components as described in [CM-8](#cm-8).

# Parameters

- `pm-05_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
