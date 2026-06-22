---
type: control
title: IA-5 - Authenticator Management
description: 'Manage system authenticators by:'
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
  description: IA-5 - Authenticator Management is part of its parent SP 800-53 structure.
- name: IA-5.1 - Password-based Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.1.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.1.
- name: IA-5.2 - Public Key-based Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.2.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.2.
- name: IA-5.3 - In-person or Trusted External Party Registration
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.3.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.3.
- name: IA-5.4 - Automated Support for Password Strength Determination
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.4.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.4.
- name: IA-5.5 - Change Authenticators Prior to Delivery
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.5.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.5.
- name: IA-5.6 - Protection of Authenticators
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.6.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.6.
- name: IA-5.7 - No Embedded Unencrypted Static Authenticators
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.7.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.7.
- name: IA-5.8 - Multiple System Accounts
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.8.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.8.
- name: IA-5.9 - Federated Credential Management
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.9.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.9.
- name: IA-5.10 - Dynamic Credential Binding
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.10.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.10.
- name: IA-5.11 - Hardware Token-based Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.11.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.11.
- name: IA-5.12 - Biometric Authentication Performance
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.12.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.12.
- name: IA-5.13 - Expiration of Cached Authenticators
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.13.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.13.
- name: IA-5.14 - Managing Content of PKI Trust Stores
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.14.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.14.
- name: IA-5.15 - GSA-approved Products and Services
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.15.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.15.
- name: IA-5.16 - In-person or Trusted External Party Authenticator Issuance
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.16.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.16.
- name: IA-5.17 - Presentation Attack Detection for Biometric Authenticators
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.17.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.17.
- name: IA-5.18 - Password Managers
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-5.18.md
  relation: has_enhancement
  description: IA-5 has enhancement IA-5.18.
nist_id: IA-5
sort_id: ia-05
implementation_level: organization
parameter_ids:
- ia-05_odp.01
- ia-05_odp.02
reference_links:
- '#678e3d6c-150b-4393-aec5-6e3481eb1e00'
- '#eea3c092-42ed-4382-a6f4-1adadef01b9d'
- '#7ba1d91c-3934-4d5a-8532-b32f864ad34c'
- '#a295ca19-8c75-4b4c-8800-98024732e181'
- '#737513fa-6758-403f-831d-5ddab5e23cb3'
- '#858705be-3c1f-48aa-a328-0ce398d95ef0'
- '#7af2e6ec-9f7e-4232-ad3f-09888eb0793a'
- '#828856bd-d7c4-427b-8b51-815517ec382d'
- '#15dc76ff-b17a-4eeb-8948-8ea8de3ccc2c'
- '#91701292-8bcd-4d2e-a5bd-59ab61e34b3c'
- '#4f5f51ac-2b8d-4b90-a3c7-46f56e967617'
- '#604774da-9e1d-48eb-9c62-4e959dc80737'
- '#81aeb0a3-d0ee-4e44-b842-6bf28d2bd7f5'
- '#ac-3'
- '#ac-6'
- '#cm-6'
- '#ia-2'
- '#ia-4'
- '#ia-7'
- '#ia-8'
- '#ia-9'
- '#ma-4'
- '#pe-2'
- '#pl-4'
- '#sc-12'
- '#sc-13'
---

# Summary

Manage system authenticators by:

# Statement

Manage system authenticators by:

# Guidance

Authenticators include passwords, cryptographic devices, biometrics, certificates, one-time password devices, and ID badges. Device authenticators include certificates and passwords. Initial authenticator content is the actual content of the authenticator (e.g., the initial password). In contrast, the requirements for authenticator content contain specific criteria or characteristics (e.g., minimum password length). Developers may deliver system components with factory default authentication credentials (i.e., passwords) to allow for initial installation and configuration. Default authentication credentials are often well known, easily discoverable, and present a significant risk. The requirement to protect individual authenticators may be implemented via control [PL-4](#pl-4) or [PS-6](#ps-6) for authenticators in the possession of individuals and by controls [AC-3](#ac-3), [AC-6](#ac-6) , and [SC-28](#sc-28) for authenticators stored in organizational systems, including passwords stored in hashed or encrypted formats or files containing encrypted or hashed passwords accessible with administrator privileges.

Systems support authenticator management by organization-defined settings and restrictions for various authenticator characteristics (e.g., minimum password length, validation time window for time synchronous one-time tokens, and number of allowed rejections during the verification stage of biometric authentication). Actions can be taken to safeguard individual authenticators, including maintaining possession of authenticators, not sharing authenticators with others, and immediately reporting lost, stolen, or compromised authenticators. Authenticator management includes issuing and revoking authenticators for temporary access when no longer needed.

# Parameters

- `ia-05_odp.01`
- `ia-05_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
