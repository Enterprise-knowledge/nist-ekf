---
type: control_enhancement
title: CM-3.5 - Automated Security Response
description: 'Implement the following security responses automatically if baseline configurations are changed in
  an unauthorized manner: {{ insert: param, cm-03.05_odp }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-3.md
  relation: part_of
  description: CM-3.5 - Automated Security Response is part of its parent SP 800-53 structure.
- name: CM-3 - Configuration Change Control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-3.md
  relation: enhances
  description: CM-3.5 enhances base control CM-3.
nist_id: CM-3.5
sort_id: cm-03.05
implementation_level: system
parameter_ids:
- cm-03.05_odp
reference_links:
- '#cm-3'
---

# Summary

Implement the following security responses automatically if baseline configurations are changed in an unauthorized manner: {{ insert: param, cm-03.05_odp }}.

# Statement

Implement the following security responses automatically if baseline configurations are changed in an unauthorized manner: {{ insert: param, cm-03.05_odp }}.

# Guidance

Automated security responses include halting selected system functions, halting system processing, and issuing alerts or notifications to organizational personnel when there is an unauthorized modification of a configuration item.

# Parameters

- `cm-03.05_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
