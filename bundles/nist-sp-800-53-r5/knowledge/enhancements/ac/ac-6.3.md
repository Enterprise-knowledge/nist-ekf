---
type: control_enhancement
title: AC-6.3 - Network Access to Privileged Commands
description: 'Authorize network access to {{ insert: param, ac-06.03_odp.01 }} only for {{ insert: param, ac-06.03_odp.02
  }} and document the rationale for such access in the security plan for the system.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-6.md
  relation: part_of
  description: AC-6.3 - Network Access to Privileged Commands is part of its parent SP 800-53 structure.
- name: AC-6 - Least Privilege
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-6.md
  relation: enhances
  description: AC-6.3 enhances base control AC-6.
nist_id: AC-6.3
sort_id: ac-06.03
implementation_level: organization
parameter_ids:
- ac-06.03_odp.01
- ac-06.03_odp.02
reference_links:
- '#ac-6'
- '#ac-17'
- '#ac-18'
- '#ac-19'
---

# Summary

Authorize network access to {{ insert: param, ac-06.03_odp.01 }} only for {{ insert: param, ac-06.03_odp.02 }} and document the rationale for such access in the security plan for the system.

# Statement

Authorize network access to {{ insert: param, ac-06.03_odp.01 }} only for {{ insert: param, ac-06.03_odp.02 }} and document the rationale for such access in the security plan for the system.

# Guidance

Network access is any access across a network connection in lieu of local access (i.e., user being physically present at the device).

# Parameters

- `ac-06.03_odp.01`
- `ac-06.03_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
