---
type: control_enhancement
title: CM-3.7 - Review System Changes
description: 'Review changes to the system {{ insert: param, cm-03.07_odp.01 }} or when {{ insert: param, cm-03.07_odp.02
  }} to determine whether unauthorized changes have occurred.'
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
- cm
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-3.md
  relation: part_of
  description: CM-3.7 - Review System Changes is part of its parent SP 800-53 structure.
- name: CM-3 - Configuration Change Control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-3.md
  relation: enhances
  description: CM-3.7 enhances base control CM-3.
nist_id: CM-3.7
sort_id: cm-03.07
implementation_level: organization
parameter_ids:
- cm-03.07_odp.01
- cm-03.07_odp.02
reference_links:
- '#cm-3'
- '#au-6'
- '#au-7'
- '#cm-3'
---

# Summary

Review changes to the system {{ insert: param, cm-03.07_odp.01 }} or when {{ insert: param, cm-03.07_odp.02 }} to determine whether unauthorized changes have occurred.

# Statement

Review changes to the system {{ insert: param, cm-03.07_odp.01 }} or when {{ insert: param, cm-03.07_odp.02 }} to determine whether unauthorized changes have occurred.

# Guidance

Indications that warrant a review of changes to the system and the specific circumstances justifying such reviews may be obtained from activities carried out by organizations during the configuration change process or continuous monitoring process.

# Parameters

- `cm-03.07_odp.01`
- `cm-03.07_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
