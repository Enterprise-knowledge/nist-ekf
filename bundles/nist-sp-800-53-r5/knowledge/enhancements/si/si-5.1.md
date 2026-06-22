---
type: control_enhancement
title: SI-5.1 - Automated Alerts and Advisories
description: 'Broadcast security alert and advisory information throughout the organization using {{ insert: param,
  si-05.01_odp }}.'
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
- si
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-5.md
  relation: part_of
  description: SI-5.1 - Automated Alerts and Advisories is part of its parent SP 800-53 structure.
- name: SI-5 - Security Alerts, Advisories, and Directives
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-5.md
  relation: enhances
  description: SI-5.1 enhances base control SI-5.
nist_id: SI-5.1
sort_id: si-05.01
implementation_level: organization
parameter_ids:
- si-05.01_odp
reference_links:
- '#si-5'
---

# Summary

Broadcast security alert and advisory information throughout the organization using {{ insert: param, si-05.01_odp }}.

# Statement

Broadcast security alert and advisory information throughout the organization using {{ insert: param, si-05.01_odp }}.

# Guidance

The significant number of changes to organizational systems and environments of operation requires the dissemination of security-related information to a variety of organizational entities that have a direct interest in the success of organizational mission and business functions. Based on information provided by security alerts and advisories, changes may be required at one or more of the three levels related to the management of risk, including the governance level, mission and business process level, and the information system level.

# Parameters

- `si-05.01_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
