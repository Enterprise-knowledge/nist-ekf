---
type: control_enhancement
title: CP-2.6 - Alternate Processing and Storage Sites
description: 'Plan for the transfer of {{ insert: param, cp-02.06_odp }} mission and business functions to alternate
  processing and/or storage sites with minimal or no loss of operational continuity and sustain that continuity
  through'
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
  description: CP-2.6 - Alternate Processing and Storage Sites is part of its parent SP 800-53 structure.
- name: CP-2 - Contingency Plan
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-2.md
  relation: enhances
  description: CP-2.6 enhances base control CP-2.
nist_id: CP-2.6
sort_id: cp-02.06
implementation_level: organization
parameter_ids:
- cp-02.06_odp
reference_links:
- '#cp-2'
---

# Summary

Plan for the transfer of {{ insert: param, cp-02.06_odp }} mission and business functions to alternate processing and/or storage sites with minimal or no loss of operational continuity and sustain that continuity through

# Statement

Plan for the transfer of {{ insert: param, cp-02.06_odp }} mission and business functions to alternate processing and/or storage sites with minimal or no loss of operational continuity and sustain that continuity through system restoration to primary processing and/or storage sites.

# Guidance

Organizations may choose to conduct contingency planning activities for alternate processing and storage sites as part of business continuity planning or business impact analyses. Primary processing and/or storage sites defined by organizations as part of contingency planning may change depending on the circumstances associated with the contingency.

# Parameters

- `cp-02.06_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
