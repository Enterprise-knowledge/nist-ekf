---
type: control
title: AC-3 - Access Enforcement
description: Enforce approved authorizations for logical access to information and system resources in accordance
  with applicable access control policies.
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
- ac
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ac.md
  relation: part_of
  description: AC-3 - Access Enforcement is part of its parent SP 800-53 structure.
- name: AC-3.1 - Restricted Access to Privileged Functions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-3.1.md
  relation: has_enhancement
  description: AC-3 has enhancement AC-3.1.
- name: AC-3.2 - Dual Authorization
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-3.2.md
  relation: has_enhancement
  description: AC-3 has enhancement AC-3.2.
- name: AC-3.3 - Mandatory Access Control
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-3.3.md
  relation: has_enhancement
  description: AC-3 has enhancement AC-3.3.
- name: AC-3.4 - Discretionary Access Control
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-3.4.md
  relation: has_enhancement
  description: AC-3 has enhancement AC-3.4.
- name: AC-3.5 - Security-relevant Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-3.5.md
  relation: has_enhancement
  description: AC-3 has enhancement AC-3.5.
- name: AC-3.6 - Protection of User and System Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-3.6.md
  relation: has_enhancement
  description: AC-3 has enhancement AC-3.6.
- name: AC-3.7 - Role-based Access Control
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-3.7.md
  relation: has_enhancement
  description: AC-3 has enhancement AC-3.7.
- name: AC-3.8 - Revocation of Access Authorizations
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-3.8.md
  relation: has_enhancement
  description: AC-3 has enhancement AC-3.8.
- name: AC-3.9 - Controlled Release
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-3.9.md
  relation: has_enhancement
  description: AC-3 has enhancement AC-3.9.
- name: AC-3.10 - Audited Override of Access Control Mechanisms
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-3.10.md
  relation: has_enhancement
  description: AC-3 has enhancement AC-3.10.
- name: AC-3.11 - Restrict Access to Specific Information Types
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-3.11.md
  relation: has_enhancement
  description: AC-3 has enhancement AC-3.11.
- name: AC-3.12 - Assert and Enforce Application Access
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-3.12.md
  relation: has_enhancement
  description: AC-3 has enhancement AC-3.12.
- name: AC-3.13 - Attribute-based Access Control
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-3.13.md
  relation: has_enhancement
  description: AC-3 has enhancement AC-3.13.
- name: AC-3.14 - Individual Access
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-3.14.md
  relation: has_enhancement
  description: AC-3 has enhancement AC-3.14.
- name: AC-3.15 - Discretionary and Mandatory Access Control
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-3.15.md
  relation: has_enhancement
  description: AC-3 has enhancement AC-3.15.
nist_id: AC-3
sort_id: ac-03
implementation_level: system
parameter_ids: []
reference_links:
- '#18e71fec-c6fd-475a-925a-5d8495cf8455'
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#110e26af-4765-49e1-8740-6750f83fcda1'
- '#e7942589-e267-4a5a-a3d9-f39a7aae81f0'
- '#8306620b-1920-4d73-8b21-12008528595f'
- '#2956e175-f674-43f4-b1b9-e074ad9fc39c'
- '#388a3aa2-5d85-4bad-b8a3-77db80d63c4f'
- '#7f473f21-fdbf-4a6c-81a1-0ab95919609d'
- '#ac-2'
- '#ac-4'
- '#ac-5'
- '#ac-6'
- '#ac-16'
- '#ac-17'
- '#ac-18'
- '#ac-19'
- '#ac-20'
- '#ac-21'
- '#ac-22'
- '#ac-24'
- '#ac-25'
- '#at-2'
- '#at-3'
- '#au-9'
- '#ca-9'
- '#cm-5'
- '#cm-11'
- '#ia-2'
- '#ia-5'
- '#ia-6'
- '#ia-7'
- '#ia-11'
- '#ia-13'
- '#ma-3'
- '#ma-4'
- '#ma-5'
- '#mp-4'
- '#pm-2'
- '#ps-3'
- '#pt-2'
- '#pt-3'
- '#sa-17'
- '#sc-2'
- '#sc-3'
- '#sc-4'
- '#sc-12'
- '#sc-13'
- '#sc-28'
- '#sc-31'
- '#sc-34'
- '#si-4'
- '#si-8'
---

# Summary

Enforce approved authorizations for logical access to information and system resources in accordance with applicable access control policies.

# Statement

Enforce approved authorizations for logical access to information and system resources in accordance with applicable access control policies.

# Guidance

Access control policies control access between active entities or subjects (i.e., users or processes acting on behalf of users) and passive entities or objects (i.e., devices, files, records, domains) in organizational systems. In addition to enforcing authorized access at the system level and recognizing that systems can host many applications and services in support of mission and business functions, access enforcement mechanisms can also be employed at the application and service level to provide increased information security and privacy. In contrast to logical access controls that are implemented within the system, physical access controls are addressed by the controls in the Physical and Environmental Protection ( [PE](#pe) ) family.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
