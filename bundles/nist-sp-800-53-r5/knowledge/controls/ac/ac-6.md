---
type: control
title: AC-6 - Least Privilege
description: Employ the principle of least privilege, allowing only authorized accesses for users (or processes
  acting on behalf of users) that are necessary to accomplish assigned organizational tasks.
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
  description: AC-6 - Least Privilege is part of its parent SP 800-53 structure.
- name: AC-6.1 - Authorize Access to Security Functions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-6.1.md
  relation: has_enhancement
  description: AC-6 has enhancement AC-6.1.
- name: AC-6.2 - Non-privileged Access for Nonsecurity Functions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-6.2.md
  relation: has_enhancement
  description: AC-6 has enhancement AC-6.2.
- name: AC-6.3 - Network Access to Privileged Commands
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-6.3.md
  relation: has_enhancement
  description: AC-6 has enhancement AC-6.3.
- name: AC-6.4 - Separate Processing Domains
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-6.4.md
  relation: has_enhancement
  description: AC-6 has enhancement AC-6.4.
- name: AC-6.5 - Privileged Accounts
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-6.5.md
  relation: has_enhancement
  description: AC-6 has enhancement AC-6.5.
- name: AC-6.6 - Privileged Access by Non-organizational Users
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-6.6.md
  relation: has_enhancement
  description: AC-6 has enhancement AC-6.6.
- name: AC-6.7 - Review of User Privileges
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-6.7.md
  relation: has_enhancement
  description: AC-6 has enhancement AC-6.7.
- name: AC-6.8 - Privilege Levels for Code Execution
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-6.8.md
  relation: has_enhancement
  description: AC-6 has enhancement AC-6.8.
- name: AC-6.9 - Log Use of Privileged Functions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-6.9.md
  relation: has_enhancement
  description: AC-6 has enhancement AC-6.9.
- name: AC-6.10 - Prohibit Non-privileged Users from Executing Privileged Functions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-6.10.md
  relation: has_enhancement
  description: AC-6 has enhancement AC-6.10.
nist_id: AC-6
sort_id: ac-06
implementation_level: organization
parameter_ids: []
reference_links:
- '#ac-2'
- '#ac-3'
- '#ac-5'
- '#ac-16'
- '#cm-5'
- '#cm-11'
- '#pl-2'
- '#pm-12'
- '#sa-8'
- '#sa-15'
- '#sa-17'
- '#sc-38'
---

# Summary

Employ the principle of least privilege, allowing only authorized accesses for users (or processes acting on behalf of users) that are necessary to accomplish assigned organizational tasks.

# Statement

Employ the principle of least privilege, allowing only authorized accesses for users (or processes acting on behalf of users) that are necessary to accomplish assigned organizational tasks.

# Guidance

Organizations employ least privilege for specific duties and systems. The principle of least privilege is also applied to system processes, ensuring that the processes have access to systems and operate at privilege levels no higher than necessary to accomplish organizational missions or business functions. Organizations consider the creation of additional processes, roles, and accounts as necessary to achieve least privilege. Organizations apply least privilege to the development, implementation, and operation of organizational systems.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
