---
type: control
title: IA-2 - Identification and Authentication (Organizational Users)
description: Uniquely identify and authenticate organizational users and associate that unique identification with
  processes acting on behalf of those users.
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
  description: IA-2 - Identification and Authentication (Organizational Users) is part of its parent SP 800-53 structure.
- name: IA-2.1 - Multi-factor Authentication to Privileged Accounts
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-2.1.md
  relation: has_enhancement
  description: IA-2 has enhancement IA-2.1.
- name: IA-2.2 - Multi-factor Authentication to Non-privileged Accounts
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-2.2.md
  relation: has_enhancement
  description: IA-2 has enhancement IA-2.2.
- name: IA-2.3 - Local Access to Privileged Accounts
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-2.3.md
  relation: has_enhancement
  description: IA-2 has enhancement IA-2.3.
- name: IA-2.4 - Local Access to Non-privileged Accounts
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-2.4.md
  relation: has_enhancement
  description: IA-2 has enhancement IA-2.4.
- name: IA-2.5 - Individual Authentication with Group Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-2.5.md
  relation: has_enhancement
  description: IA-2 has enhancement IA-2.5.
- name: IA-2.6 - Access to Accounts —separate Device
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-2.6.md
  relation: has_enhancement
  description: IA-2 has enhancement IA-2.6.
- name: IA-2.7 - Network Access to Non-privileged Accounts — Separate Device
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-2.7.md
  relation: has_enhancement
  description: IA-2 has enhancement IA-2.7.
- name: IA-2.8 - Access to Accounts — Replay Resistant
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-2.8.md
  relation: has_enhancement
  description: IA-2 has enhancement IA-2.8.
- name: IA-2.9 - Network Access to Non-privileged Accounts — Replay Resistant
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-2.9.md
  relation: has_enhancement
  description: IA-2 has enhancement IA-2.9.
- name: IA-2.10 - Single Sign-on
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-2.10.md
  relation: has_enhancement
  description: IA-2 has enhancement IA-2.10.
- name: IA-2.11 - Remote Access — Separate Device
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-2.11.md
  relation: has_enhancement
  description: IA-2 has enhancement IA-2.11.
- name: IA-2.12 - Acceptance of PIV Credentials
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-2.12.md
  relation: has_enhancement
  description: IA-2 has enhancement IA-2.12.
- name: IA-2.13 - Out-of-band Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-2.13.md
  relation: has_enhancement
  description: IA-2 has enhancement IA-2.13.
nist_id: IA-2
sort_id: ia-02
implementation_level: organization
parameter_ids: []
reference_links:
- '#678e3d6c-150b-4393-aec5-6e3481eb1e00'
- '#7ba1d91c-3934-4d5a-8532-b32f864ad34c'
- '#a295ca19-8c75-4b4c-8800-98024732e181'
- '#737513fa-6758-403f-831d-5ddab5e23cb3'
- '#858705be-3c1f-48aa-a328-0ce398d95ef0'
- '#7af2e6ec-9f7e-4232-ad3f-09888eb0793a'
- '#828856bd-d7c4-427b-8b51-815517ec382d'
- '#10963761-58fc-4b20-b3d6-b44a54daba03'
- '#d9e036ba-6eec-46a6-9340-b0bf1fea23b4'
- '#e8552d48-cf41-40aa-8b06-f45f7fb4706c'
- '#15dc76ff-b17a-4eeb-8948-8ea8de3ccc2c'
- '#4b38e961-1125-4a5b-aa35-1d6c02846dad'
- '#91701292-8bcd-4d2e-a5bd-59ab61e34b3c'
- '#4f5f51ac-2b8d-4b90-a3c7-46f56e967617'
- '#604774da-9e1d-48eb-9c62-4e959dc80737'
- '#7f473f21-fdbf-4a6c-81a1-0ab95919609d'
- '#3915a084-b87b-4f02-83d4-c369e746292f'
- '#ac-2'
- '#ac-3'
- '#ac-4'
- '#ac-14'
- '#ac-17'
- '#ac-18'
- '#au-1'
- '#au-6'
- '#ia-4'
- '#ia-5'
- '#ia-8'
- '#ia-13'
- '#ma-4'
- '#ma-5'
- '#pe-2'
- '#pl-4'
- '#sa-4'
- '#sa-8'
---

# Summary

Uniquely identify and authenticate organizational users and associate that unique identification with processes acting on behalf of those users.

# Statement

Uniquely identify and authenticate organizational users and associate that unique identification with processes acting on behalf of those users.

# Guidance

Organizations can satisfy the identification and authentication requirements by complying with the requirements in [HSPD 12](#f16e438e-7114-4144-bfe2-2dfcad8cb2d0) . Organizational users include employees or individuals who organizations consider to have an equivalent status to employees (e.g., contractors and guest researchers). Unique identification and authentication of users applies to all accesses other than those that are explicitly identified in [AC-14](#ac-14) and that occur through the authorized use of group authenticators without individual authentication. Since processes execute on behalf of groups and roles, organizations may require unique identification of individuals in group accounts or for detailed accountability of individual activity.

Organizations employ passwords, physical authenticators, or biometrics to authenticate user identities or, in the case of multi-factor authentication, some combination thereof. Access to organizational systems is defined as either local access or network access. Local access is any access to organizational systems by users or processes acting on behalf of users, where access is obtained through direct connections without the use of networks. Network access is access to organizational systems by users (or processes acting on behalf of users) where access is obtained through network connections (i.e., nonlocal accesses). Remote access is a type of network access that involves communication through external networks. Internal networks include local area networks and wide area networks.

The use of encrypted virtual private networks for network connections between organization-controlled endpoints and non-organization-controlled endpoints may be treated as internal networks with respect to protecting the confidentiality and integrity of information traversing the network. Identification and authentication requirements for non-organizational users are described in [IA-8](#ia-8).

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
