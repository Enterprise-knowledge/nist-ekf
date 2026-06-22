---
type: control_enhancement
title: SI-4.20 - Privileged Users
description: 'Implement the following additional monitoring of privileged users: {{ insert: param, si-04.20_odp
  }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-4.md
  relation: part_of
  description: SI-4.20 - Privileged Users is part of its parent SP 800-53 structure.
- name: SI-4 - System Monitoring
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-4.md
  relation: enhances
  description: SI-4.20 enhances base control SI-4.
nist_id: SI-4.20
sort_id: si-04.20
implementation_level: system
parameter_ids:
- si-04.20_odp
reference_links:
- '#si-4'
- '#ac-18'
---

# Summary

Implement the following additional monitoring of privileged users: {{ insert: param, si-04.20_odp }}.

# Statement

Implement the following additional monitoring of privileged users: {{ insert: param, si-04.20_odp }}.

# Guidance

Privileged users have access to more sensitive information, including security-related information, than the general user population. Access to such information means that privileged users can potentially do greater damage to systems and organizations than non-privileged users. Therefore, implementing additional monitoring on privileged users helps to ensure that organizations can identify malicious activity at the earliest possible time and take appropriate actions.

# Parameters

- `si-04.20_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
