---
type: control_enhancement
title: AC-4.10 - Enable and Disable Security or Privacy Policy Filters
description: 'Provide the capability for privileged administrators to enable and disable {{ insert: param, ac-4.10_prm_1
  }} under the following conditions: {{ insert: param, ac-4.10_prm_2 }}.'
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
- ac
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-4.md
  relation: part_of
  description: AC-4.10 - Enable and Disable Security or Privacy Policy Filters is part of its parent SP 800-53 structure.
- name: AC-4 - Information Flow Enforcement
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-4.md
  relation: enhances
  description: AC-4.10 enhances base control AC-4.
nist_id: AC-4.10
sort_id: ac-04.10
implementation_level: system
parameter_ids:
- ac-4.10_prm_1
- ac-4.10_prm_2
- ac-04.10_odp.01
- ac-04.10_odp.02
- ac-04.10_odp.03
- ac-04.10_odp.04
reference_links:
- '#ac-4'
---

# Summary

Provide the capability for privileged administrators to enable and disable {{ insert: param, ac-4.10_prm_1 }} under the following conditions: {{ insert: param, ac-4.10_prm_2 }}.

# Statement

Provide the capability for privileged administrators to enable and disable {{ insert: param, ac-4.10_prm_1 }} under the following conditions: {{ insert: param, ac-4.10_prm_2 }}.

# Guidance

For example, as allowed by the system authorization, administrators can enable security or privacy policy filters to accommodate approved data types. Administrators also have the capability to select the filters that are executed on a specific data flow based on the type of data that is being transferred, the source and destination security domains, and other security or privacy relevant features, as needed.

# Parameters

- `ac-4.10_prm_1`
- `ac-4.10_prm_2`
- `ac-04.10_odp.01`
- `ac-04.10_odp.02`
- `ac-04.10_odp.03`
- `ac-04.10_odp.04`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
