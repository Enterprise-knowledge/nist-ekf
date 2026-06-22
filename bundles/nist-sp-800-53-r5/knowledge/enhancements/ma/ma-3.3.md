---
type: control_enhancement
title: MA-3.3 - Prevent Unauthorized Removal
description: 'Prevent the removal of maintenance equipment containing organizational information by:'
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
- ma
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-3.md
  relation: part_of
  description: MA-3.3 - Prevent Unauthorized Removal is part of its parent SP 800-53 structure.
- name: MA-3 - Maintenance Tools
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-3.md
  relation: enhances
  description: MA-3.3 enhances base control MA-3.
nist_id: MA-3.3
sort_id: ma-03.03
implementation_level: organization
parameter_ids:
- ma-03.03_odp
reference_links:
- '#ma-3'
- '#mp-6'
---

# Summary

Prevent the removal of maintenance equipment containing organizational information by:

# Statement

Prevent the removal of maintenance equipment containing organizational information by:

# Guidance

Organizational information includes all information owned by organizations and any information provided to organizations for which the organizations serve as information stewards.

# Parameters

- `ma-03.03_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
