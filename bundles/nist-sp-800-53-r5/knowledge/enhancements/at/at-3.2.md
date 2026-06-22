---
type: control_enhancement
title: AT-3.2 - Physical Security Controls
description: 'Provide {{ insert: param, at-03.02_odp.01 }} with initial and {{ insert: param, at-03.02_odp.02 }}
  training in the employment and operation of physical security controls.'
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
  description: AT-3.2 - Physical Security Controls is part of its parent SP 800-53 structure.
- name: AT-3 - Role-based Training
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/at/at-3.md
  relation: enhances
  description: AT-3.2 enhances base control AT-3.
nist_id: AT-3.2
sort_id: at-03.02
implementation_level: organization
parameter_ids:
- at-03.02_odp.01
- at-03.02_odp.02
reference_links:
- '#at-3'
- '#pe-2'
- '#pe-3'
- '#pe-4'
---

# Summary

Provide {{ insert: param, at-03.02_odp.01 }} with initial and {{ insert: param, at-03.02_odp.02 }} training in the employment and operation of physical security controls.

# Statement

Provide {{ insert: param, at-03.02_odp.01 }} with initial and {{ insert: param, at-03.02_odp.02 }} training in the employment and operation of physical security controls.

# Guidance

Physical security controls include physical access control devices, physical intrusion and detection alarms, operating procedures for facility security guards, and monitoring or surveillance equipment.

# Parameters

- `at-03.02_odp.01`
- `at-03.02_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
