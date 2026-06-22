---
type: control
title: PE-4 - Access Control for Transmission
description: 'Control physical access to {{ insert: param, pe-04_odp.01 }} within organizational facilities using
  {{ insert: param, pe-04_odp.02 }}.'
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/pe.md
  relation: part_of
  description: PE-4 - Access Control for Transmission is part of its parent SP 800-53 structure.
nist_id: PE-4
sort_id: pe-04
implementation_level: organization
parameter_ids:
- pe-04_odp.01
- pe-04_odp.02
reference_links:
- '#at-3'
- '#ia-4'
- '#mp-2'
- '#mp-4'
- '#pe-2'
- '#pe-3'
- '#pe-5'
- '#pe-9'
- '#sc-7'
- '#sc-8'
---

# Summary

Control physical access to {{ insert: param, pe-04_odp.01 }} within organizational facilities using {{ insert: param, pe-04_odp.02 }}.

# Statement

Control physical access to {{ insert: param, pe-04_odp.01 }} within organizational facilities using {{ insert: param, pe-04_odp.02 }}.

# Guidance

Security controls applied to system distribution and transmission lines prevent accidental damage, disruption, and physical tampering. Such controls may also be necessary to prevent eavesdropping or modification of unencrypted transmissions. Security controls used to control physical access to system distribution and transmission lines include disconnected or locked spare jacks, locked wiring closets, protection of cabling by conduit or cable trays, and wiretapping sensors.

# Parameters

- `pe-04_odp.01`
- `pe-04_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
