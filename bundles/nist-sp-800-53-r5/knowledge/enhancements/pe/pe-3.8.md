---
type: control_enhancement
title: PE-3.8 - Access Control Vestibules
description: 'Employ access control vestibules at {{ insert: param, pe-03.08_odp }}.'
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
- pe
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-3.md
  relation: part_of
  description: PE-3.8 - Access Control Vestibules is part of its parent SP 800-53 structure.
- name: PE-3 - Physical Access Control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-3.md
  relation: enhances
  description: PE-3.8 enhances base control PE-3.
nist_id: PE-3.8
sort_id: pe-03.08
implementation_level: organization
parameter_ids:
- pe-03.08_odp
reference_links:
- '#pe-3'
---

# Summary

Employ access control vestibules at {{ insert: param, pe-03.08_odp }}.

# Statement

Employ access control vestibules at {{ insert: param, pe-03.08_odp }}.

# Guidance

An access control vestibule is part of a physical access control system that typically provides a space between two sets of interlocking doors. Vestibules are designed to prevent unauthorized individuals from following authorized individuals into facilities with controlled access. This activity, also known as piggybacking or tailgating, results in unauthorized access to the facility. Interlocking door controllers can be used to limit the number of individuals who enter controlled access points and to provide containment areas while authorization for physical access is verified. Interlocking door controllers can be fully automated (i.e., controlling the opening and closing of the doors) or partially automated (i.e., using security guards to control the number of individuals entering the containment area).

# Parameters

- `pe-03.08_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
