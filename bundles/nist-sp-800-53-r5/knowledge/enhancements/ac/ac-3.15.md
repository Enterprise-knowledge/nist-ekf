---
type: control_enhancement
title: AC-3.15 - Discretionary and Mandatory Access Control
description: SP 800-53 control AC-3.15.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-3.md
  relation: part_of
  description: AC-3.15 - Discretionary and Mandatory Access Control is part of its parent SP 800-53 structure.
- name: AC-3 - Access Enforcement
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-3.md
  relation: enhances
  description: AC-3.15 enhances base control AC-3.
nist_id: AC-3.15
sort_id: ac-03.15
implementation_level: system
parameter_ids:
- ac-3.15_prm_1
- ac-3.15_prm_2
- ac-03.15_odp.01
- ac-03.15_odp.02
- ac-03.15_odp.03
- ac-03.15_odp.04
reference_links:
- '#ac-3'
- '#sc-2'
- '#sc-3'
- '#ac-4'
---

# Summary

SP 800-53 control AC-3.15.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Simultaneously implementing a mandatory access control policy and a discretionary access control policy can provide additional protection against the unauthorized execution of code by users or processes acting on behalf of users. This helps prevent a single compromised user or process from compromising the entire system.

# Parameters

- `ac-3.15_prm_1`
- `ac-3.15_prm_2`
- `ac-03.15_odp.01`
- `ac-03.15_odp.02`
- `ac-03.15_odp.03`
- `ac-03.15_odp.04`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
