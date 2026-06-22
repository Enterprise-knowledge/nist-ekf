---
type: control_enhancement
title: CM-8.4 - Accountability Information
description: 'Include in the system component inventory information, a means for identifying by {{ insert: param,
  cm-08.04_odp }} , individuals responsible and accountable for administering those components.'
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
- cm
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-8.md
  relation: part_of
  description: CM-8.4 - Accountability Information is part of its parent SP 800-53 structure.
- name: CM-8 - System Component Inventory
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-8.md
  relation: enhances
  description: CM-8.4 enhances base control CM-8.
nist_id: CM-8.4
sort_id: cm-08.04
implementation_level: organization
parameter_ids:
- cm-08.04_odp
reference_links:
- '#cm-8'
- '#ac-3'
---

# Summary

Include in the system component inventory information, a means for identifying by {{ insert: param, cm-08.04_odp }} , individuals responsible and accountable for administering those components.

# Statement

Include in the system component inventory information, a means for identifying by {{ insert: param, cm-08.04_odp }} , individuals responsible and accountable for administering those components.

# Guidance

Identifying individuals who are responsible and accountable for administering system components ensures that the assigned components are properly administered and that organizations can contact those individuals if some action is required (e.g., when the component is determined to be the source of a breach, needs to be recalled or replaced, or needs to be relocated).

# Parameters

- `cm-08.04_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
