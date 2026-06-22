---
type: control_enhancement
title: AC-2.9 - Restrictions on Use of Shared and Group Accounts
description: 'Only permit the use of shared and group accounts that meet {{ insert: param, ac-02.09_odp }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-2.md
  relation: part_of
  description: AC-2.9 - Restrictions on Use of Shared and Group Accounts is part of its parent SP 800-53 structure.
- name: AC-2 - Account Management
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-2.md
  relation: enhances
  description: AC-2.9 enhances base control AC-2.
nist_id: AC-2.9
sort_id: ac-02.09
implementation_level: organization
parameter_ids:
- ac-02.09_odp
reference_links:
- '#ac-2'
---

# Summary

Only permit the use of shared and group accounts that meet {{ insert: param, ac-02.09_odp }}.

# Statement

Only permit the use of shared and group accounts that meet {{ insert: param, ac-02.09_odp }}.

# Guidance

Before permitting the use of shared or group accounts, organizations consider the increased risk due to the lack of accountability with such accounts.

# Parameters

- `ac-02.09_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
