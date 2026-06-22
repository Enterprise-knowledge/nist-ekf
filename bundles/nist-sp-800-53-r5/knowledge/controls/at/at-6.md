---
type: control
title: AT-6 - Training Feedback
description: 'Provide feedback on organizational training results to the following personnel {{ insert: param, at-06_odp.01
  }}: {{ insert: param, at-06_odp.02 }}.'
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control
- at
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/at.md
  relation: part_of
  description: AT-6 - Training Feedback is part of its parent SP 800-53 structure.
nist_id: AT-6
sort_id: at-06
implementation_level: organization
parameter_ids:
- at-06_odp.01
- at-06_odp.02
reference_links: []
---

# Summary

Provide feedback on organizational training results to the following personnel {{ insert: param, at-06_odp.01 }}: {{ insert: param, at-06_odp.02 }}.

# Statement

Provide feedback on organizational training results to the following personnel {{ insert: param, at-06_odp.01 }}: {{ insert: param, at-06_odp.02 }}.

# Guidance

Training feedback includes awareness training results and role-based training results. Training results, especially failures of personnel in critical roles, can be indicative of a potentially serious problem. Therefore, it is important that senior managers are made aware of such situations so that they can take appropriate response actions. Training feedback supports the evaluation and update of organizational training described in [AT-2b](#at-2_smt.b) and [AT-3b](#at-3_smt.b).

# Parameters

- `at-06_odp.01`
- `at-06_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
