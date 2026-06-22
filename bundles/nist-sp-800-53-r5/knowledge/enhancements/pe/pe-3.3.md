---
type: control_enhancement
title: PE-3.3 - Continuous Guards
description: 'Employ guards to control {{ insert: param, pe-03.03_odp }} to the facility where the system resides
  24 hours per day, 7 days per week.'
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
  description: PE-3.3 - Continuous Guards is part of its parent SP 800-53 structure.
- name: PE-3 - Physical Access Control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-3.md
  relation: enhances
  description: PE-3.3 enhances base control PE-3.
nist_id: PE-3.3
sort_id: pe-03.03
implementation_level: organization
parameter_ids:
- pe-03.03_odp
reference_links:
- '#pe-3'
- '#cp-6'
- '#cp-7'
- '#pe-6'
---

# Summary

Employ guards to control {{ insert: param, pe-03.03_odp }} to the facility where the system resides 24 hours per day, 7 days per week.

# Statement

Employ guards to control {{ insert: param, pe-03.03_odp }} to the facility where the system resides 24 hours per day, 7 days per week.

# Guidance

Employing guards at selected physical access points to the facility provides a more rapid response capability for organizations. Guards also provide the opportunity for human surveillance in areas of the facility not covered by video surveillance.

# Parameters

- `pe-03.03_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
