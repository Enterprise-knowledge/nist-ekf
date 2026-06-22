---
type: control
title: CP-9 - System Backup
description: SP 800-53 control CP-9.
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
- cp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/cp.md
  relation: part_of
  description: CP-9 - System Backup is part of its parent SP 800-53 structure.
- name: CP-9.1 - Testing for Reliability and Integrity
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-9.1.md
  relation: has_enhancement
  description: CP-9 has enhancement CP-9.1.
- name: CP-9.2 - Test Restoration Using Sampling
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-9.2.md
  relation: has_enhancement
  description: CP-9 has enhancement CP-9.2.
- name: CP-9.3 - Separate Storage for Critical Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-9.3.md
  relation: has_enhancement
  description: CP-9 has enhancement CP-9.3.
- name: CP-9.4 - Protection from Unauthorized Modification
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-9.4.md
  relation: has_enhancement
  description: CP-9 has enhancement CP-9.4.
- name: CP-9.5 - Transfer to Alternate Storage Site
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-9.5.md
  relation: has_enhancement
  description: CP-9 has enhancement CP-9.5.
- name: CP-9.6 - Redundant Secondary System
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-9.6.md
  relation: has_enhancement
  description: CP-9 has enhancement CP-9.6.
- name: CP-9.7 - Dual Authorization for Deletion or Destruction
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-9.7.md
  relation: has_enhancement
  description: CP-9 has enhancement CP-9.7.
- name: CP-9.8 - Cryptographic Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-9.8.md
  relation: has_enhancement
  description: CP-9 has enhancement CP-9.8.
nist_id: CP-9
sort_id: cp-09
implementation_level: organization
parameter_ids:
- cp-09_odp.01
- cp-09_odp.02
- cp-09_odp.03
- cp-09_odp.04
reference_links:
- '#678e3d6c-150b-4393-aec5-6e3481eb1e00'
- '#7c37a38d-21d7-40d8-bc3d-b5e27eac17e1'
- '#bc39f179-c735-4da2-b7a7-b2b622119755'
- '#3653e316-8923-430e-8943-b3b2b2562fc6'
- '#2494df28-9049-4196-b233-540e7440993f'
- '#cp-2'
- '#cp-6'
- '#cp-10'
- '#mp-4'
- '#mp-5'
- '#sc-8'
- '#sc-12'
- '#sc-13'
- '#si-4'
- '#si-13'
---

# Summary

SP 800-53 control CP-9.

# Statement

No statement text was present in the OSCAL record.

# Guidance

System-level information includes system state information, operating system software, middleware, application software, and licenses. User-level information includes information other than system-level information. Mechanisms employed to protect the integrity of system backups include digital signatures and cryptographic hashes. Protection of system backup information while in transit is addressed by [MP-5](#mp-5) and [SC-8](#sc-8) . System backups reflect the requirements in contingency plans as well as other organizational requirements for backing up information. Organizations may be subject to laws, executive orders, directives, regulations, or policies with requirements regarding specific categories of information (e.g., personal health information). Organizational personnel consult with the senior agency official for privacy and legal counsel regarding such requirements.

# Parameters

- `cp-09_odp.01`
- `cp-09_odp.02`
- `cp-09_odp.03`
- `cp-09_odp.04`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
