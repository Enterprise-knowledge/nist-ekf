---
type: control_enhancement
title: CP-2.3 - Resume Mission and Business Functions
description: 'Plan for the resumption of {{ insert: param, cp-02.03_odp.01 }} mission and business functions within
  {{ insert: param, cp-02.03_odp.02 }} of contingency plan activation.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-2.md
  relation: part_of
  description: CP-2.3 - Resume Mission and Business Functions is part of its parent SP 800-53 structure.
- name: CP-2 - Contingency Plan
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-2.md
  relation: enhances
  description: CP-2.3 enhances base control CP-2.
nist_id: CP-2.3
sort_id: cp-02.03
implementation_level: organization
parameter_ids:
- cp-02.03_odp.01
- cp-02.03_odp.02
reference_links:
- '#cp-2'
---

# Summary

Plan for the resumption of {{ insert: param, cp-02.03_odp.01 }} mission and business functions within {{ insert: param, cp-02.03_odp.02 }} of contingency plan activation.

# Statement

Plan for the resumption of {{ insert: param, cp-02.03_odp.01 }} mission and business functions within {{ insert: param, cp-02.03_odp.02 }} of contingency plan activation.

# Guidance

Organizations may choose to conduct contingency planning activities to resume mission and business functions as part of business continuity planning or as part of business impact analyses. Organizations prioritize the resumption of mission and business functions. The time period for resuming mission and business functions may be dependent on the severity and extent of the disruptions to the system and its supporting infrastructure.

# Parameters

- `cp-02.03_odp.01`
- `cp-02.03_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
