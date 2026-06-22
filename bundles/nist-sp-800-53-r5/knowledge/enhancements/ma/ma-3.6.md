---
type: control_enhancement
title: MA-3.6 - Software Updates and Patches
description: Inspect maintenance tools to ensure the latest software updates and patches are installed.
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
- ma
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-3.md
  relation: part_of
  description: MA-3.6 - Software Updates and Patches is part of its parent SP 800-53 structure.
- name: MA-3 - Maintenance Tools
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-3.md
  relation: enhances
  description: MA-3.6 enhances base control MA-3.
nist_id: MA-3.6
sort_id: ma-03.06
implementation_level: organization
parameter_ids: []
reference_links:
- '#ma-3'
- '#ac-3'
- '#ac-6'
---

# Summary

Inspect maintenance tools to ensure the latest software updates and patches are installed.

# Statement

Inspect maintenance tools to ensure the latest software updates and patches are installed.

# Guidance

Maintenance tools using outdated and/or unpatched software can provide a threat vector for adversaries and result in a significant vulnerability for organizations.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
