---
type: control_enhancement
title: AC-7.2 - Purge or Wipe Mobile Device
description: 'Purge or wipe information from {{ insert: param, ac-07.02_odp.01 }} based on {{ insert: param, ac-07.02_odp.02
  }} after {{ insert: param, ac-07.02_odp.03 }} consecutive, unsuccessful device logon attempts.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-7.md
  relation: part_of
  description: AC-7.2 - Purge or Wipe Mobile Device is part of its parent SP 800-53 structure.
- name: AC-7 - Unsuccessful Logon Attempts
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-7.md
  relation: enhances
  description: AC-7.2 enhances base control AC-7.
nist_id: AC-7.2
sort_id: ac-07.02
implementation_level: system
parameter_ids:
- ac-07.02_odp.01
- ac-07.02_odp.02
- ac-07.02_odp.03
reference_links:
- '#ac-7'
- '#ac-19'
- '#mp-5'
- '#mp-6'
---

# Summary

Purge or wipe information from {{ insert: param, ac-07.02_odp.01 }} based on {{ insert: param, ac-07.02_odp.02 }} after {{ insert: param, ac-07.02_odp.03 }} consecutive, unsuccessful device logon attempts.

# Statement

Purge or wipe information from {{ insert: param, ac-07.02_odp.01 }} based on {{ insert: param, ac-07.02_odp.02 }} after {{ insert: param, ac-07.02_odp.03 }} consecutive, unsuccessful device logon attempts.

# Guidance

A mobile device is a computing device that has a small form factor such that it can be carried by a single individual; is designed to operate without a physical connection; possesses local, non-removable or removable data storage; and includes a self-contained power source. Purging or wiping the device applies only to mobile devices for which the organization-defined number of unsuccessful logons occurs. The logon is to the mobile device, not to any one account on the device. Successful logons to accounts on mobile devices reset the unsuccessful logon count to zero. Purging or wiping may be unnecessary if the information on the device is protected with sufficiently strong encryption mechanisms.

# Parameters

- `ac-07.02_odp.01`
- `ac-07.02_odp.02`
- `ac-07.02_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
