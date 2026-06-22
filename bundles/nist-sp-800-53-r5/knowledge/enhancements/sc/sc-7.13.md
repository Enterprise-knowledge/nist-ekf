---
type: control_enhancement
title: SC-7.13 - Isolation of Security Tools, Mechanisms, and Support Components
description: 'Isolate {{ insert: param, sc-07.13_odp }} from other internal system components by implementing physically
  separate subnetworks with managed interfaces to other components of the system.'
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
- sc
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-7.md
  relation: part_of
  description: SC-7.13 - Isolation of Security Tools, Mechanisms, and Support Components is part of its parent SP
    800-53 structure.
- name: SC-7 - Boundary Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-7.md
  relation: enhances
  description: SC-7.13 enhances base control SC-7.
nist_id: SC-7.13
sort_id: sc-07.13
implementation_level: system
parameter_ids:
- sc-07.13_odp
reference_links:
- '#sc-7'
- '#sc-2'
- '#sc-3'
---

# Summary

Isolate {{ insert: param, sc-07.13_odp }} from other internal system components by implementing physically separate subnetworks with managed interfaces to other components of the system.

# Statement

Isolate {{ insert: param, sc-07.13_odp }} from other internal system components by implementing physically separate subnetworks with managed interfaces to other components of the system.

# Guidance

Physically separate subnetworks with managed interfaces are useful in isolating computer network defenses from critical operational processing networks to prevent adversaries from discovering the analysis and forensics techniques employed by organizations.

# Parameters

- `sc-07.13_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
