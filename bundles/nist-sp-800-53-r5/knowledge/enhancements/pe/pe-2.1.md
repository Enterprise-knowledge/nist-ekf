---
type: control_enhancement
title: PE-2.1 - Access by Position or Role
description: Authorize physical access to the facility where the system resides based on position or role.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-2.md
  relation: part_of
  description: PE-2.1 - Access by Position or Role is part of its parent SP 800-53 structure.
- name: PE-2 - Physical Access Authorizations
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-2.md
  relation: enhances
  description: PE-2.1 enhances base control PE-2.
nist_id: PE-2.1
sort_id: pe-02.01
implementation_level: organization
parameter_ids: []
reference_links:
- '#pe-2'
- '#ac-2'
- '#ac-3'
- '#ac-6'
---

# Summary

Authorize physical access to the facility where the system resides based on position or role.

# Statement

Authorize physical access to the facility where the system resides based on position or role.

# Guidance

Role-based facility access includes access by authorized permanent and regular/routine maintenance personnel, duty officers, and emergency medical staff.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
