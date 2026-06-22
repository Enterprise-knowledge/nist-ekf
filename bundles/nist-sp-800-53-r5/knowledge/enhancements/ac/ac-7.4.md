---
type: control_enhancement
title: AC-7.4 - Use of Alternate Authentication Factor
description: SP 800-53 control AC-7.4.
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
  description: AC-7.4 - Use of Alternate Authentication Factor is part of its parent SP 800-53 structure.
- name: AC-7 - Unsuccessful Logon Attempts
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-7.md
  relation: enhances
  description: AC-7.4 enhances base control AC-7.
nist_id: AC-7.4
sort_id: ac-07.04
implementation_level: organization
parameter_ids:
- ac-07.04_odp.01
- ac-07.04_odp.02
- ac-07.04_odp.03
reference_links:
- '#ac-7'
- '#ia-3'
---

# Summary

SP 800-53 control AC-7.4.

# Statement

No statement text was present in the OSCAL record.

# Guidance

The use of alternate authentication factors supports the objective of availability and allows a user who has inadvertently been locked out to use additional authentication factors to bypass the lockout.

# Parameters

- `ac-07.04_odp.01`
- `ac-07.04_odp.02`
- `ac-07.04_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
