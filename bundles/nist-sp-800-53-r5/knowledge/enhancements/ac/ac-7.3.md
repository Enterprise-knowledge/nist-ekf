---
type: control_enhancement
title: AC-7.3 - Biometric Attempt Limiting
description: 'Limit the number of unsuccessful biometric logon attempts to {{ insert: param, ac-07.03_odp }}.'
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
  description: AC-7.3 - Biometric Attempt Limiting is part of its parent SP 800-53 structure.
- name: AC-7 - Unsuccessful Logon Attempts
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-7.md
  relation: enhances
  description: AC-7.3 enhances base control AC-7.
nist_id: AC-7.3
sort_id: ac-07.03
implementation_level: organization
parameter_ids:
- ac-07.03_odp
reference_links:
- '#ac-7'
- '#ia-3'
---

# Summary

Limit the number of unsuccessful biometric logon attempts to {{ insert: param, ac-07.03_odp }}.

# Statement

Limit the number of unsuccessful biometric logon attempts to {{ insert: param, ac-07.03_odp }}.

# Guidance

Biometrics are probabilistic in nature. The ability to successfully authenticate can be impacted by many factors, including matching performance and presentation attack detection mechanisms. Organizations select the appropriate number of attempts for users based on organizationally-defined factors.

# Parameters

- `ac-07.03_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
