---
type: control_enhancement
title: AC-9.4 - Additional Logon Information
description: 'Notify the user, upon successful logon, of the following additional information: {{ insert: param,
  ac-09.04_odp }}.'
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
  description: AC-9.4 - Additional Logon Information is part of its parent SP 800-53 structure.
- name: AC-9 - Previous Logon Notification
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-9.md
  relation: enhances
  description: AC-9.4 enhances base control AC-9.
nist_id: AC-9.4
sort_id: ac-09.04
implementation_level: system
parameter_ids:
- ac-09.04_odp
reference_links:
- '#ac-9'
---

# Summary

Notify the user, upon successful logon, of the following additional information: {{ insert: param, ac-09.04_odp }}.

# Statement

Notify the user, upon successful logon, of the following additional information: {{ insert: param, ac-09.04_odp }}.

# Guidance

Organizations can specify additional information to be provided to users upon logon, including the location of the last logon. User location is defined as information that can be determined by systems, such as Internet Protocol (IP) addresses from which network logons occurred, notifications of local logons, or device identifiers.

# Parameters

- `ac-09.04_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
