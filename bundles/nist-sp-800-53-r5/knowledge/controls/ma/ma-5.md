---
type: control
title: MA-5 - Maintenance Personnel
description: SP 800-53 control MA-5.
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ma.md
  relation: part_of
  description: MA-5 - Maintenance Personnel is part of its parent SP 800-53 structure.
- name: MA-5.1 - Individuals Without Appropriate Access
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-5.1.md
  relation: has_enhancement
  description: MA-5 has enhancement MA-5.1.
- name: MA-5.2 - Security Clearances for Classified Systems
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-5.2.md
  relation: has_enhancement
  description: MA-5 has enhancement MA-5.2.
- name: MA-5.3 - Citizenship Requirements for Classified Systems
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-5.3.md
  relation: has_enhancement
  description: MA-5 has enhancement MA-5.3.
- name: MA-5.4 - Foreign Nationals
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-5.4.md
  relation: has_enhancement
  description: MA-5 has enhancement MA-5.4.
- name: MA-5.5 - Non-system Maintenance
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-5.5.md
  relation: has_enhancement
  description: MA-5 has enhancement MA-5.5.
nist_id: MA-5
sort_id: ma-05
implementation_level: organization
parameter_ids: []
reference_links:
- '#ac-2'
- '#ac-3'
- '#ac-5'
- '#ac-6'
- '#ia-2'
- '#ia-8'
- '#ma-4'
- '#mp-2'
- '#pe-2'
- '#pe-3'
- '#ps-7'
- '#ra-3'
---

# Summary

SP 800-53 control MA-5.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Maintenance personnel refers to individuals who perform hardware or software maintenance on organizational systems, while [PE-2](#pe-2) addresses physical access for individuals whose maintenance duties place them within the physical protection perimeter of the systems. Technical competence of supervising individuals relates to the maintenance performed on the systems, while having required access authorizations refers to maintenance on and near the systems. Individuals not previously identified as authorized maintenance personnel—such as information technology manufacturers, vendors, systems integrators, and consultants—may require privileged access to organizational systems, such as when they are required to conduct maintenance activities with little or no notice. Based on organizational assessments of risk, organizations may issue temporary credentials to these individuals. Temporary credentials may be for one-time use or for very limited time periods.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
