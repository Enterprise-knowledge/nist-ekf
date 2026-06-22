---
type: control_enhancement
title: AC-9.3 - Notification of Account Changes
description: 'Notify the user, upon successful logon, of changes to {{ insert: param, ac-09.03_odp.01 }} during
  {{ insert: param, ac-09.03_odp.02 }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-9.md
  relation: part_of
  description: AC-9.3 - Notification of Account Changes is part of its parent SP 800-53 structure.
- name: AC-9 - Previous Logon Notification
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-9.md
  relation: enhances
  description: AC-9.3 enhances base control AC-9.
nist_id: AC-9.3
sort_id: ac-09.03
implementation_level: system
parameter_ids:
- ac-09.03_odp.01
- ac-09.03_odp.02
reference_links:
- '#ac-9'
---

# Summary

Notify the user, upon successful logon, of changes to {{ insert: param, ac-09.03_odp.01 }} during {{ insert: param, ac-09.03_odp.02 }}.

# Statement

Notify the user, upon successful logon, of changes to {{ insert: param, ac-09.03_odp.01 }} during {{ insert: param, ac-09.03_odp.02 }}.

# Guidance

Information about changes to security-related account characteristics within a specified time period allows users to recognize if changes were made without their knowledge.

# Parameters

- `ac-09.03_odp.01`
- `ac-09.03_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
