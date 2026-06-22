---
type: control_enhancement
title: AT-3.1 - Environmental Controls
description: 'Provide {{ insert: param, at-03.01_odp.01 }} with initial and {{ insert: param, at-03.01_odp.02 }}
  training in the employment and operation of environmental controls.'
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
- at
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/at/at-3.md
  relation: part_of
  description: AT-3.1 - Environmental Controls is part of its parent SP 800-53 structure.
- name: AT-3 - Role-based Training
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/at/at-3.md
  relation: enhances
  description: AT-3.1 enhances base control AT-3.
nist_id: AT-3.1
sort_id: at-03.01
implementation_level: organization
parameter_ids:
- at-03.01_odp.01
- at-03.01_odp.02
reference_links:
- '#at-3'
- '#pe-1'
- '#pe-11'
- '#pe-13'
- '#pe-14'
- '#pe-15'
---

# Summary

Provide {{ insert: param, at-03.01_odp.01 }} with initial and {{ insert: param, at-03.01_odp.02 }} training in the employment and operation of environmental controls.

# Statement

Provide {{ insert: param, at-03.01_odp.01 }} with initial and {{ insert: param, at-03.01_odp.02 }} training in the employment and operation of environmental controls.

# Guidance

Environmental controls include fire suppression and detection devices or systems, sprinkler systems, handheld fire extinguishers, fixed fire hoses, smoke detectors, temperature or humidity, heating, ventilation, air conditioning, and power within the facility.

# Parameters

- `at-03.01_odp.01`
- `at-03.01_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
