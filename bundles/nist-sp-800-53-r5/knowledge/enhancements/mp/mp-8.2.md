---
type: control_enhancement
title: MP-8.2 - Equipment Testing
description: 'Test downgrading equipment and procedures {{ insert: param, mp-8.2_prm_1 }} to ensure that downgrading
  actions are being achieved.'
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
- mp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-8.md
  relation: part_of
  description: MP-8.2 - Equipment Testing is part of its parent SP 800-53 structure.
- name: MP-8 - Media Downgrading
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-8.md
  relation: enhances
  description: MP-8.2 enhances base control MP-8.
nist_id: MP-8.2
sort_id: mp-08.02
implementation_level: organization
parameter_ids:
- mp-8.2_prm_1
- mp-08.02_odp.01
- mp-08.02_odp.02
reference_links:
- '#mp-8'
---

# Summary

Test downgrading equipment and procedures {{ insert: param, mp-8.2_prm_1 }} to ensure that downgrading actions are being achieved.

# Statement

Test downgrading equipment and procedures {{ insert: param, mp-8.2_prm_1 }} to ensure that downgrading actions are being achieved.

# Guidance

None.

# Parameters

- `mp-8.2_prm_1`
- `mp-08.02_odp.01`
- `mp-08.02_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
