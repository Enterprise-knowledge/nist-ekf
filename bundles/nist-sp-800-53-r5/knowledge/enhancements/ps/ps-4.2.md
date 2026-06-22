---
type: control_enhancement
title: PS-4.2 - Automated Actions
description: 'Use {{ insert: param, ps-04.02_odp.01 }} to {{ insert: param, ps-04.02_odp.02 }}.'
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
- ps
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ps/ps-4.md
  relation: part_of
  description: PS-4.2 - Automated Actions is part of its parent SP 800-53 structure.
- name: PS-4 - Personnel Termination
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ps/ps-4.md
  relation: enhances
  description: PS-4.2 enhances base control PS-4.
nist_id: PS-4.2
sort_id: ps-04.02
implementation_level: organization
parameter_ids:
- ps-04.02_odp.01
- ps-04.02_odp.02
- ps-04.02_odp.03
reference_links:
- '#ps-4'
---

# Summary

Use {{ insert: param, ps-04.02_odp.01 }} to {{ insert: param, ps-04.02_odp.02 }}.

# Statement

Use {{ insert: param, ps-04.02_odp.01 }} to {{ insert: param, ps-04.02_odp.02 }}.

# Guidance

In organizations with many employees, not all personnel who need to know about termination actions receive the appropriate notifications, or if such notifications are received, they may not occur in a timely manner. Automated mechanisms can be used to send automatic alerts or notifications to organizational personnel or roles when individuals are terminated. Such automatic alerts or notifications can be conveyed in a variety of ways, including via telephone, electronic mail, text message, or websites. Automated mechanisms can also be employed to quickly and thoroughly disable access to system resources after an employee is terminated.

# Parameters

- `ps-04.02_odp.01`
- `ps-04.02_odp.02`
- `ps-04.02_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
