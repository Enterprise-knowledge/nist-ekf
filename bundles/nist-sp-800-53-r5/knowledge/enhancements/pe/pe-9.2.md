---
type: control_enhancement
title: PE-9.2 - Automatic Voltage Controls
description: 'Employ automatic voltage controls for {{ insert: param, pe-09.02_odp }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-9.md
  relation: part_of
  description: PE-9.2 - Automatic Voltage Controls is part of its parent SP 800-53 structure.
- name: PE-9 - Power Equipment and Cabling
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-9.md
  relation: enhances
  description: PE-9.2 enhances base control PE-9.
nist_id: PE-9.2
sort_id: pe-09.02
implementation_level: organization
parameter_ids:
- pe-09.02_odp
reference_links:
- '#pe-9'
---

# Summary

Employ automatic voltage controls for {{ insert: param, pe-09.02_odp }}.

# Statement

Employ automatic voltage controls for {{ insert: param, pe-09.02_odp }}.

# Guidance

Automatic voltage controls can monitor and control voltage. Such controls include voltage regulators, voltage conditioners, and voltage stabilizers.

# Parameters

- `pe-09.02_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
