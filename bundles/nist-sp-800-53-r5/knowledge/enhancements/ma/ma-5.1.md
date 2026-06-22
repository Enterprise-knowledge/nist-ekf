---
type: control_enhancement
title: MA-5.1 - Individuals Without Appropriate Access
description: SP 800-53 control MA-5.1.
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
  description: MA-5.1 - Individuals Without Appropriate Access is part of its parent SP 800-53 structure.
- name: MA-5 - Maintenance Personnel
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-5.md
  relation: enhances
  description: MA-5.1 enhances base control MA-5.
nist_id: MA-5.1
sort_id: ma-05.01
implementation_level: organization
parameter_ids:
- ma-05.01_odp
reference_links:
- '#ma-5'
- '#mp-6'
- '#pl-2'
---

# Summary

SP 800-53 control MA-5.1.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Procedures for individuals who lack appropriate security clearances or who are not U.S. citizens are intended to deny visual and electronic access to classified or controlled unclassified information contained on organizational systems. Procedures for the use of maintenance personnel can be documented in security plans for the systems.

# Parameters

- `ma-05.01_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
