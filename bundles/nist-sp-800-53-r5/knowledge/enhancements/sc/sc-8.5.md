---
type: control_enhancement
title: SC-8.5 - Protected Distribution System
description: 'Implement {{ insert: param, sc-08.05_odp.01 }} to {{ insert: param, sc-08.05_odp.02 }} during transmission.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-8.md
  relation: part_of
  description: SC-8.5 - Protected Distribution System is part of its parent SP 800-53 structure.
- name: SC-8 - Transmission Confidentiality and Integrity
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-8.md
  relation: enhances
  description: SC-8.5 enhances base control SC-8.
nist_id: SC-8.5
sort_id: sc-08.05
implementation_level: system
parameter_ids:
- sc-08.05_odp.01
- sc-08.05_odp.02
reference_links:
- '#sc-8'
---

# Summary

Implement {{ insert: param, sc-08.05_odp.01 }} to {{ insert: param, sc-08.05_odp.02 }} during transmission.

# Statement

Implement {{ insert: param, sc-08.05_odp.01 }} to {{ insert: param, sc-08.05_odp.02 }} during transmission.

# Guidance

The purpose of a protected distribution system is to deter, detect, and/or make difficult physical access to the communication lines that carry national security information.

# Parameters

- `sc-08.05_odp.01`
- `sc-08.05_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
