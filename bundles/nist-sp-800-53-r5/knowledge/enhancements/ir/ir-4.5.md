---
type: control_enhancement
title: IR-4.5 - Automatic Disabling of System
description: 'Implement a configurable capability to automatically disable the system if {{ insert: param, ir-04.05_odp
  }} are detected.'
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
- ir
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-4.md
  relation: part_of
  description: IR-4.5 - Automatic Disabling of System is part of its parent SP 800-53 structure.
- name: IR-4 - Incident Handling
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-4.md
  relation: enhances
  description: IR-4.5 enhances base control IR-4.
nist_id: IR-4.5
sort_id: ir-04.05
implementation_level: organization
parameter_ids:
- ir-04.05_odp
reference_links:
- '#ir-4'
---

# Summary

Implement a configurable capability to automatically disable the system if {{ insert: param, ir-04.05_odp }} are detected.

# Statement

Implement a configurable capability to automatically disable the system if {{ insert: param, ir-04.05_odp }} are detected.

# Guidance

Organizations consider whether the capability to automatically disable the system conflicts with continuity of operations requirements specified as part of [CP-2](#cp-2) or [IR-4(3)](#ir-4.3) . Security violations include cyber-attacks that have compromised the integrity of the system or exfiltrated organizational information and serious errors in software programs that could adversely impact organizational missions or functions or jeopardize the safety of individuals.

# Parameters

- `ir-04.05_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
