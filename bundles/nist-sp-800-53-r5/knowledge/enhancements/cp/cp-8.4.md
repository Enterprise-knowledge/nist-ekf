---
type: control_enhancement
title: CP-8.4 - Provider Contingency Plan
description: SP 800-53 control CP-8.4.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-8.md
  relation: part_of
  description: CP-8.4 - Provider Contingency Plan is part of its parent SP 800-53 structure.
- name: CP-8 - Telecommunications Services
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-8.md
  relation: enhances
  description: CP-8.4 enhances base control CP-8.
nist_id: CP-8.4
sort_id: cp-08.04
implementation_level: organization
parameter_ids:
- cp-8.4_prm_1
- cp-08.04_odp.01
- cp-08.04_odp.02
reference_links:
- '#cp-8'
- '#cp-3'
- '#cp-4'
---

# Summary

SP 800-53 control CP-8.4.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Reviews of provider contingency plans consider the proprietary nature of such plans. In some situations, a summary of provider contingency plans may be sufficient evidence for organizations to satisfy the review requirement. Telecommunications service providers may also participate in ongoing disaster recovery exercises in coordination with the Department of Homeland Security and state and local governments. Organizations may use these types of activities to satisfy evidentiary requirements related to service provider contingency plan reviews, testing, and training.

# Parameters

- `cp-8.4_prm_1`
- `cp-08.04_odp.01`
- `cp-08.04_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
