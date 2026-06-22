---
type: control_enhancement
title: PM-7.1 - Offloading
description: 'Offload {{ insert: param, pm-07.01_odp }} to other systems, system components, or an external provider.'
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
- pm
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pm/pm-7.md
  relation: part_of
  description: PM-7.1 - Offloading is part of its parent SP 800-53 structure.
- name: PM-7 - Enterprise Architecture
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pm/pm-7.md
  relation: enhances
  description: PM-7.1 enhances base control PM-7.
nist_id: PM-7.1
sort_id: pm-07.01
implementation_level: organization
parameter_ids:
- pm-07.01_odp
reference_links:
- '#pm-7'
- '#sa-8'
---

# Summary

Offload {{ insert: param, pm-07.01_odp }} to other systems, system components, or an external provider.

# Statement

Offload {{ insert: param, pm-07.01_odp }} to other systems, system components, or an external provider.

# Guidance

Not every function or service that a system provides is essential to organizational mission or business functions. Printing or copying is an example of a non-essential but supporting service for an organization. Whenever feasible, such supportive but non-essential functions or services are not co-located with the functions or services that support essential mission or business functions. Maintaining such functions on the same system or system component increases the attack surface of the organization’s mission-essential functions or services. Moving supportive but non-essential functions to a non-critical system, system component, or external provider can also increase efficiency by putting those functions or services under the control of individuals or providers who are subject matter experts in the functions or services.

# Parameters

- `pm-07.01_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
