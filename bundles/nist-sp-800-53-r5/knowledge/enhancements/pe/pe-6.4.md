---
type: control_enhancement
title: PE-6.4 - Monitoring Physical Access to Systems
description: 'Monitor physical access to the system in addition to the physical access monitoring of the facility
  at {{ insert: param, pe-06.04_odp }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-6.md
  relation: part_of
  description: PE-6.4 - Monitoring Physical Access to Systems is part of its parent SP 800-53 structure.
- name: PE-6 - Monitoring Physical Access
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-6.md
  relation: enhances
  description: PE-6.4 enhances base control PE-6.
nist_id: PE-6.4
sort_id: pe-06.04
implementation_level: organization
parameter_ids:
- pe-06.04_odp
reference_links:
- '#pe-6'
---

# Summary

Monitor physical access to the system in addition to the physical access monitoring of the facility at {{ insert: param, pe-06.04_odp }}.

# Statement

Monitor physical access to the system in addition to the physical access monitoring of the facility at {{ insert: param, pe-06.04_odp }}.

# Guidance

Monitoring physical access to systems provides additional monitoring for those areas within facilities where there is a concentration of system components, including server rooms, media storage areas, and communications centers. Physical access monitoring can be coordinated with intrusion detection systems and system monitoring capabilities to provide comprehensive and integrated threat coverage for the organization.

# Parameters

- `pe-06.04_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
