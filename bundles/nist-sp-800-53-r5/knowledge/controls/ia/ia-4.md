---
type: control
title: IA-4 - Identifier Management
description: 'Manage system identifiers by:'
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
- ia
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ia.md
  relation: part_of
  description: IA-4 - Identifier Management is part of its parent SP 800-53 structure.
- name: IA-4.1 - Prohibit Account Identifiers as Public Identifiers
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-4.1.md
  relation: has_enhancement
  description: IA-4 has enhancement IA-4.1.
- name: IA-4.2 - Supervisor Authorization
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-4.2.md
  relation: has_enhancement
  description: IA-4 has enhancement IA-4.2.
- name: IA-4.3 - Multiple Forms of Certification
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-4.3.md
  relation: has_enhancement
  description: IA-4 has enhancement IA-4.3.
- name: IA-4.4 - Identify User Status
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-4.4.md
  relation: has_enhancement
  description: IA-4 has enhancement IA-4.4.
- name: IA-4.5 - Dynamic Management
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-4.5.md
  relation: has_enhancement
  description: IA-4 has enhancement IA-4.5.
- name: IA-4.6 - Cross-organization Management
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-4.6.md
  relation: has_enhancement
  description: IA-4 has enhancement IA-4.6.
- name: IA-4.7 - In-person Registration
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-4.7.md
  relation: has_enhancement
  description: IA-4 has enhancement IA-4.7.
- name: IA-4.8 - Pairwise Pseudonymous Identifiers
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-4.8.md
  relation: has_enhancement
  description: IA-4 has enhancement IA-4.8.
- name: IA-4.9 - Attribute Maintenance and Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-4.9.md
  relation: has_enhancement
  description: IA-4 has enhancement IA-4.9.
nist_id: IA-4
sort_id: ia-04
implementation_level: organization
parameter_ids:
- ia-04_odp.01
- ia-04_odp.02
reference_links:
- '#7ba1d91c-3934-4d5a-8532-b32f864ad34c'
- '#737513fa-6758-403f-831d-5ddab5e23cb3'
- '#858705be-3c1f-48aa-a328-0ce398d95ef0'
- '#7af2e6ec-9f7e-4232-ad3f-09888eb0793a'
- '#828856bd-d7c4-427b-8b51-815517ec382d'
- '#ac-5'
- '#ia-2'
- '#ia-3'
- '#ia-5'
- '#ia-8'
- '#ia-9'
- '#ia-12'
- '#ma-4'
- '#pe-2'
- '#pe-3'
- '#pe-4'
- '#pl-4'
- '#pm-12'
- '#ps-3'
- '#ps-4'
- '#ps-5'
- '#sc-37'
---

# Summary

Manage system identifiers by:

# Statement

Manage system identifiers by:

# Guidance

Common device identifiers include Media Access Control (MAC) addresses, Internet Protocol (IP) addresses, or device-unique token identifiers. The management of individual identifiers is not applicable to shared system accounts. Typically, individual identifiers are the usernames of the system accounts assigned to those individuals. In such instances, the account management activities of [AC-2](#ac-2) use account names provided by [IA-4](#ia-4) . Identifier management also addresses individual identifiers not necessarily associated with system accounts. Preventing the reuse of identifiers implies preventing the assignment of previously used individual, group, role, service, or device identifiers to different individuals, groups, roles, services, or devices.

# Parameters

- `ia-04_odp.01`
- `ia-04_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
