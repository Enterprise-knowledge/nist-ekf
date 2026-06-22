---
type: control
title: PE-3 - Physical Access Control
description: SP 800-53 control PE-3.
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/pe.md
  relation: part_of
  description: PE-3 - Physical Access Control is part of its parent SP 800-53 structure.
- name: PE-3.1 - System Access
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-3.1.md
  relation: has_enhancement
  description: PE-3 has enhancement PE-3.1.
- name: PE-3.2 - Facility and Systems
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-3.2.md
  relation: has_enhancement
  description: PE-3 has enhancement PE-3.2.
- name: PE-3.3 - Continuous Guards
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-3.3.md
  relation: has_enhancement
  description: PE-3 has enhancement PE-3.3.
- name: PE-3.4 - Lockable Casings
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-3.4.md
  relation: has_enhancement
  description: PE-3 has enhancement PE-3.4.
- name: PE-3.5 - Tamper Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-3.5.md
  relation: has_enhancement
  description: PE-3 has enhancement PE-3.5.
- name: PE-3.6 - Facility Penetration Testing
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-3.6.md
  relation: has_enhancement
  description: PE-3 has enhancement PE-3.6.
- name: PE-3.7 - Physical Barriers
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-3.7.md
  relation: has_enhancement
  description: PE-3 has enhancement PE-3.7.
- name: PE-3.8 - Access Control Vestibules
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-3.8.md
  relation: has_enhancement
  description: PE-3 has enhancement PE-3.8.
nist_id: PE-3
sort_id: pe-03
implementation_level: organization
parameter_ids:
- pe-3_prm_9
- pe-03_odp.01
- pe-03_odp.02
- pe-03_odp.03
- pe-03_odp.04
- pe-03_odp.05
- pe-03_odp.06
- pe-03_odp.07
- pe-03_odp.08
- pe-03_odp.09
- pe-03_odp.10
reference_links:
- '#7ba1d91c-3934-4d5a-8532-b32f864ad34c'
- '#858705be-3c1f-48aa-a328-0ce398d95ef0'
- '#7af2e6ec-9f7e-4232-ad3f-09888eb0793a'
- '#828856bd-d7c4-427b-8b51-815517ec382d'
- '#2100332a-16a5-4598-bacf-7261baea9711'
- '#at-3'
- '#au-2'
- '#au-6'
- '#au-9'
- '#au-13'
- '#cp-10'
- '#ia-3'
- '#ia-8'
- '#ma-5'
- '#mp-2'
- '#mp-4'
- '#pe-2'
- '#pe-4'
- '#pe-5'
- '#pe-8'
- '#ps-2'
- '#ps-3'
- '#ps-6'
- '#ps-7'
- '#ra-3'
- '#sc-28'
- '#si-4'
- '#sr-3'
---

# Summary

SP 800-53 control PE-3.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Physical access control applies to employees and visitors. Individuals with permanent physical access authorizations are not considered visitors. Physical access controls for publicly accessible areas may include physical access control logs/records, guards, or physical access devices and barriers to prevent movement from publicly accessible areas to non-public areas. Organizations determine the types of guards needed, including professional security staff, system users, or administrative staff. Physical access devices include keys, locks, combinations, biometric readers, and card readers. Physical access control systems comply with applicable laws, executive orders, directives, policies, regulations, standards, and guidelines. Organizations have flexibility in the types of audit logs employed. Audit logs can be procedural, automated, or some combination thereof. Physical access points can include facility access points, interior access points to systems that require supplemental access controls, or both. Components of systems may be in areas designated as publicly accessible with organizations controlling access to the components.

# Parameters

- `pe-3_prm_9`
- `pe-03_odp.01`
- `pe-03_odp.02`
- `pe-03_odp.03`
- `pe-03_odp.04`
- `pe-03_odp.05`
- `pe-03_odp.06`
- `pe-03_odp.07`
- `pe-03_odp.08`
- `pe-03_odp.09`
- `pe-03_odp.10`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
