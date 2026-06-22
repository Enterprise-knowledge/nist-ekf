---
type: control_enhancement
title: SC-7.28 - Connections to Public Networks
description: 'Prohibit the direct connection of {{ insert: param, sc-07.28_odp }} to a public network.'
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
  description: SC-7.28 - Connections to Public Networks is part of its parent SP 800-53 structure.
- name: SC-7 - Boundary Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-7.md
  relation: enhances
  description: SC-7.28 enhances base control SC-7.
nist_id: SC-7.28
sort_id: sc-07.28
implementation_level: organization
parameter_ids:
- sc-07.28_odp
reference_links:
- '#sc-7'
---

# Summary

Prohibit the direct connection of {{ insert: param, sc-07.28_odp }} to a public network.

# Statement

Prohibit the direct connection of {{ insert: param, sc-07.28_odp }} to a public network.

# Guidance

A direct connection is a dedicated physical or virtual connection between two or more systems. A public network is a network accessible to the public, including the Internet and organizational extranets with public access.

# Parameters

- `sc-07.28_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
