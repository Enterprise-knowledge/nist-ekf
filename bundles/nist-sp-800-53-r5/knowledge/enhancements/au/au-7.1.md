---
type: control_enhancement
title: AU-7.1 - Automatic Processing
description: 'Provide and implement the capability to process, sort, and search audit records for events of interest
  based on the following content: {{ insert: param, au-07.01_odp }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-7.md
  relation: part_of
  description: AU-7.1 - Automatic Processing is part of its parent SP 800-53 structure.
- name: AU-7 - Audit Record Reduction and Report Generation
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-7.md
  relation: enhances
  description: AU-7.1 enhances base control AU-7.
nist_id: AU-7.1
sort_id: au-07.01
implementation_level: system
parameter_ids:
- au-07.01_odp
reference_links:
- '#au-7'
---

# Summary

Provide and implement the capability to process, sort, and search audit records for events of interest based on the following content: {{ insert: param, au-07.01_odp }}.

# Statement

Provide and implement the capability to process, sort, and search audit records for events of interest based on the following content: {{ insert: param, au-07.01_odp }}.

# Guidance

Events of interest can be identified by the content of audit records, including system resources involved, information objects accessed, identities of individuals, event types, event locations, event dates and times, Internet Protocol addresses involved, or event success or failure. Organizations may define event criteria to any degree of granularity required, such as locations selectable by a general networking location or by specific system component.

# Parameters

- `au-07.01_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
