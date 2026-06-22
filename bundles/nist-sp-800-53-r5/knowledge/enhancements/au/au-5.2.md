---
type: control_enhancement
title: AU-5.2 - Real-time Alerts
description: 'Provide an alert within {{ insert: param, au-05.02_odp.01 }} to {{ insert: param, au-05.02_odp.02
  }} when the following audit failure events occur: {{ insert: param, au-05.02_odp.03 }}.'
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
- au
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-5.md
  relation: part_of
  description: AU-5.2 - Real-time Alerts is part of its parent SP 800-53 structure.
- name: AU-5 - Response to Audit Logging Process Failures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-5.md
  relation: enhances
  description: AU-5.2 enhances base control AU-5.
nist_id: AU-5.2
sort_id: au-05.02
implementation_level: system
parameter_ids:
- au-05.02_odp.01
- au-05.02_odp.02
- au-05.02_odp.03
reference_links:
- '#au-5'
---

# Summary

Provide an alert within {{ insert: param, au-05.02_odp.01 }} to {{ insert: param, au-05.02_odp.02 }} when the following audit failure events occur: {{ insert: param, au-05.02_odp.03 }}.

# Statement

Provide an alert within {{ insert: param, au-05.02_odp.01 }} to {{ insert: param, au-05.02_odp.02 }} when the following audit failure events occur: {{ insert: param, au-05.02_odp.03 }}.

# Guidance

Alerts provide organizations with urgent messages. Real-time alerts provide these messages at information technology speed (i.e., the time from event detection to alert occurs in seconds or less).

# Parameters

- `au-05.02_odp.01`
- `au-05.02_odp.02`
- `au-05.02_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
