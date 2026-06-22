---
type: control_enhancement
title: SC-4.2 - Multilevel or Periods Processing
description: 'Prevent unauthorized information transfer via shared resources in accordance with {{ insert: param,
  sc-04.02_odp }} when system processing explicitly switches between different information classification levels
  or securi'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-4.md
  relation: part_of
  description: SC-4.2 - Multilevel or Periods Processing is part of its parent SP 800-53 structure.
- name: SC-4 - Information in Shared System Resources
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-4.md
  relation: enhances
  description: SC-4.2 enhances base control SC-4.
nist_id: SC-4.2
sort_id: sc-04.02
implementation_level: system
parameter_ids:
- sc-04.02_odp
reference_links:
- '#sc-4'
---

# Summary

Prevent unauthorized information transfer via shared resources in accordance with {{ insert: param, sc-04.02_odp }} when system processing explicitly switches between different information classification levels or securi

# Statement

Prevent unauthorized information transfer via shared resources in accordance with {{ insert: param, sc-04.02_odp }} when system processing explicitly switches between different information classification levels or security categories.

# Guidance

Changes in processing levels can occur during multilevel or periods processing with information at different classification levels or security categories. It can also occur during serial reuse of hardware components at different classification levels. Organization-defined procedures can include approved sanitization processes for electronically stored information.

# Parameters

- `sc-04.02_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
