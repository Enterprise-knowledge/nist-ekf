---
type: control_enhancement
title: CP-9.5 - Transfer to Alternate Storage Site
description: 'Transfer system backup information to the alternate storage site {{ insert: param, cp-9.5_prm_1 }}.'
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
  description: CP-9.5 - Transfer to Alternate Storage Site is part of its parent SP 800-53 structure.
- name: CP-9 - System Backup
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-9.md
  relation: enhances
  description: CP-9.5 enhances base control CP-9.
nist_id: CP-9.5
sort_id: cp-09.05
implementation_level: organization
parameter_ids:
- cp-9.5_prm_1
- cp-09.05_odp.01
- cp-09.05_odp.02
reference_links:
- '#cp-9'
- '#cp-7'
- '#mp-3'
- '#mp-4'
- '#mp-5'
---

# Summary

Transfer system backup information to the alternate storage site {{ insert: param, cp-9.5_prm_1 }}.

# Statement

Transfer system backup information to the alternate storage site {{ insert: param, cp-9.5_prm_1 }}.

# Guidance

System backup information can be transferred to alternate storage sites either electronically or by the physical shipment of storage media.

# Parameters

- `cp-9.5_prm_1`
- `cp-09.05_odp.01`
- `cp-09.05_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
