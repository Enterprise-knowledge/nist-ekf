---
type: control_enhancement
title: PS-3.3 - Information Requiring Special Protective Measures
description: 'Verify that individuals accessing a system processing, storing, or transmitting information requiring
  special protection:'
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
- ps
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ps/ps-3.md
  relation: part_of
  description: PS-3.3 - Information Requiring Special Protective Measures is part of its parent SP 800-53 structure.
- name: PS-3 - Personnel Screening
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ps/ps-3.md
  relation: enhances
  description: PS-3.3 enhances base control PS-3.
nist_id: PS-3.3
sort_id: ps-03.03
implementation_level: organization
parameter_ids:
- ps-03.03_odp
reference_links:
- '#ps-3'
---

# Summary

Verify that individuals accessing a system processing, storing, or transmitting information requiring special protection:

# Statement

Verify that individuals accessing a system processing, storing, or transmitting information requiring special protection:

# Guidance

Organizational information that requires special protection includes controlled unclassified information. Personnel security criteria include position sensitivity background screening requirements.

# Parameters

- `ps-03.03_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
