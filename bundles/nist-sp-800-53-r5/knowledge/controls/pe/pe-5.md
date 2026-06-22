---
type: control
title: PE-5 - Access Control for Output Devices
description: 'Control physical access to output from {{ insert: param, pe-05_odp }} to prevent unauthorized individuals
  from obtaining the output.'
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/pe.md
  relation: part_of
  description: PE-5 - Access Control for Output Devices is part of its parent SP 800-53 structure.
- name: PE-5.1 - Access to Output by Authorized Individuals
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-5.1.md
  relation: has_enhancement
  description: PE-5 has enhancement PE-5.1.
- name: PE-5.2 - Link to Individual Identity
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-5.2.md
  relation: has_enhancement
  description: PE-5 has enhancement PE-5.2.
- name: PE-5.3 - Marking Output Devices
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-5.3.md
  relation: has_enhancement
  description: PE-5 has enhancement PE-5.3.
nist_id: PE-5
sort_id: pe-05
implementation_level: organization
parameter_ids:
- pe-05_odp
reference_links:
- '#4c501da5-9d79-4cb6-ba80-97260e1ce327'
- '#pe-2'
- '#pe-3'
- '#pe-4'
- '#pe-18'
---

# Summary

Control physical access to output from {{ insert: param, pe-05_odp }} to prevent unauthorized individuals from obtaining the output.

# Statement

Control physical access to output from {{ insert: param, pe-05_odp }} to prevent unauthorized individuals from obtaining the output.

# Guidance

Controlling physical access to output devices includes placing output devices in locked rooms or other secured areas with keypad or card reader access controls and allowing access to authorized individuals only, placing output devices in locations that can be monitored by personnel, installing monitor or screen filters, and using headphones. Examples of output devices include monitors, printers, scanners, audio devices, facsimile machines, and copiers.

# Parameters

- `pe-05_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
