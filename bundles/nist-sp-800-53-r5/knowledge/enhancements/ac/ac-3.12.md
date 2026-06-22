---
type: control_enhancement
title: AC-3.12 - Assert and Enforce Application Access
description: SP 800-53 control AC-3.12.
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
  description: AC-3.12 - Assert and Enforce Application Access is part of its parent SP 800-53 structure.
- name: AC-3 - Access Enforcement
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-3.md
  relation: enhances
  description: AC-3.12 enhances base control AC-3.
nist_id: AC-3.12
sort_id: ac-03.12
implementation_level: system
parameter_ids:
- ac-03.12_odp
reference_links:
- '#ac-3'
- '#cm-7'
---

# Summary

SP 800-53 control AC-3.12.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Asserting and enforcing application access is intended to address applications that need to access existing system applications and functions, including user contacts, global positioning systems, cameras, keyboards, microphones, networks, phones, or other files.

# Parameters

- `ac-03.12_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
