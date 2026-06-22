---
type: control
title: AU-9 - Protection of Audit Information
description: SP 800-53 control AU-9.
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
- au
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/au.md
  relation: part_of
  description: AU-9 - Protection of Audit Information is part of its parent SP 800-53 structure.
- name: AU-9.1 - Hardware Write-once Media
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-9.1.md
  relation: has_enhancement
  description: AU-9 has enhancement AU-9.1.
- name: AU-9.2 - Store on Separate Physical Systems or Components
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-9.2.md
  relation: has_enhancement
  description: AU-9 has enhancement AU-9.2.
- name: AU-9.3 - Cryptographic Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-9.3.md
  relation: has_enhancement
  description: AU-9 has enhancement AU-9.3.
- name: AU-9.4 - Access by Subset of Privileged Users
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-9.4.md
  relation: has_enhancement
  description: AU-9 has enhancement AU-9.4.
- name: AU-9.5 - Dual Authorization
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-9.5.md
  relation: has_enhancement
  description: AU-9 has enhancement AU-9.5.
- name: AU-9.6 - Read-only Access
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-9.6.md
  relation: has_enhancement
  description: AU-9 has enhancement AU-9.6.
- name: AU-9.7 - Store on Component with Different Operating System
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-9.7.md
  relation: has_enhancement
  description: AU-9 has enhancement AU-9.7.
nist_id: AU-9
sort_id: au-09
implementation_level: system
parameter_ids:
- au-09_odp
reference_links:
- '#678e3d6c-150b-4393-aec5-6e3481eb1e00'
- '#eea3c092-42ed-4382-a6f4-1adadef01b9d'
- '#a295ca19-8c75-4b4c-8800-98024732e181'
- '#ac-3'
- '#ac-6'
- '#au-6'
- '#au-11'
- '#au-14'
- '#au-15'
- '#mp-2'
- '#mp-4'
- '#pe-2'
- '#pe-3'
- '#pe-6'
- '#sa-8'
- '#sc-8'
- '#si-4'
---

# Summary

SP 800-53 control AU-9.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Audit information includes all information needed to successfully audit system activity, such as audit records, audit log settings, audit reports, and personally identifiable information. Audit logging tools are those programs and devices used to conduct system audit and logging activities. Protection of audit information focuses on technical protection and limits the ability to access and execute audit logging tools to authorized individuals. Physical protection of audit information is addressed by both media protection controls and physical and environmental protection controls.

# Parameters

- `au-09_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
