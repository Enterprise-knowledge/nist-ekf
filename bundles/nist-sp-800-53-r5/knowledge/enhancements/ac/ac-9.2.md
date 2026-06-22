---
type: control_enhancement
title: AC-9.2 - Successful and Unsuccessful Logons
description: 'Notify the user, upon successful logon, of the number of {{ insert: param, ac-09.02_odp.01 }} during
  {{ insert: param, ac-09.02_odp.02 }}.'
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
  description: AC-9.2 - Successful and Unsuccessful Logons is part of its parent SP 800-53 structure.
- name: AC-9 - Previous Logon Notification
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-9.md
  relation: enhances
  description: AC-9.2 enhances base control AC-9.
nist_id: AC-9.2
sort_id: ac-09.02
implementation_level: system
parameter_ids:
- ac-09.02_odp.01
- ac-09.02_odp.02
reference_links:
- '#ac-9'
---

# Summary

Notify the user, upon successful logon, of the number of {{ insert: param, ac-09.02_odp.01 }} during {{ insert: param, ac-09.02_odp.02 }}.

# Statement

Notify the user, upon successful logon, of the number of {{ insert: param, ac-09.02_odp.01 }} during {{ insert: param, ac-09.02_odp.02 }}.

# Guidance

Information about the number of successful and unsuccessful logon attempts within a specified time period allows the user to recognize if the number and type of logon attempts are consistent with the user’s actual logon attempts.

# Parameters

- `ac-09.02_odp.01`
- `ac-09.02_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
