---
type: control_enhancement
title: MA-5.5 - Non-system Maintenance
description: Ensure that non-escorted personnel performing maintenance activities not directly associated with the
  system but in the physical proximity of the system, have required access authorizations.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-5.md
  relation: part_of
  description: MA-5.5 - Non-system Maintenance is part of its parent SP 800-53 structure.
- name: MA-5 - Maintenance Personnel
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-5.md
  relation: enhances
  description: MA-5.5 enhances base control MA-5.
nist_id: MA-5.5
sort_id: ma-05.05
implementation_level: organization
parameter_ids: []
reference_links:
- '#ma-5'
---

# Summary

Ensure that non-escorted personnel performing maintenance activities not directly associated with the system but in the physical proximity of the system, have required access authorizations.

# Statement

Ensure that non-escorted personnel performing maintenance activities not directly associated with the system but in the physical proximity of the system, have required access authorizations.

# Guidance

Personnel who perform maintenance activities in other capacities not directly related to the system include physical plant personnel and custodial personnel.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
