---
type: control_enhancement
title: PE-9.1 - Redundant Cabling
description: 'Employ redundant power cabling paths that are physically separated by {{ insert: param, pe-09.01_odp
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
  description: PE-9.1 - Redundant Cabling is part of its parent SP 800-53 structure.
- name: PE-9 - Power Equipment and Cabling
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-9.md
  relation: enhances
  description: PE-9.1 enhances base control PE-9.
nist_id: PE-9.1
sort_id: pe-09.01
implementation_level: organization
parameter_ids:
- pe-09.01_odp
reference_links:
- '#pe-9'
---

# Summary

Employ redundant power cabling paths that are physically separated by {{ insert: param, pe-09.01_odp }}.

# Statement

Employ redundant power cabling paths that are physically separated by {{ insert: param, pe-09.01_odp }}.

# Guidance

Physically separate and redundant power cables ensure that power continues to flow in the event that one of the cables is cut or otherwise damaged.

# Parameters

- `pe-09.01_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
