---
type: control_family
title: IA - Identification and Authentication
description: SP 800-53 control family for Identification and Authentication.
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control-family
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
- name: The Controls
  path: /bundles/nist-sp-800-53-r5/knowledge/sections/controls.md
  relation: part_of
  description: This family is part of the controls section.
- name: IA-1 - Policy and Procedures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-1.md
  relation: contains
  description: The family contains control IA-1.
- name: IA-2 - Identification and Authentication (Organizational Users)
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-2.md
  relation: contains
  description: The family contains control IA-2.
- name: IA-3 - Device Identification and Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-3.md
  relation: contains
  description: The family contains control IA-3.
- name: IA-4 - Identifier Management
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-4.md
  relation: contains
  description: The family contains control IA-4.
- name: IA-5 - Authenticator Management
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-5.md
  relation: contains
  description: The family contains control IA-5.
- name: IA-6 - Authentication Feedback
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-6.md
  relation: contains
  description: The family contains control IA-6.
- name: IA-7 - Cryptographic Module Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-7.md
  relation: contains
  description: The family contains control IA-7.
- name: IA-8 - Identification and Authentication (Non-organizational Users)
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-8.md
  relation: contains
  description: The family contains control IA-8.
- name: IA-9 - Service Identification and Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-9.md
  relation: contains
  description: The family contains control IA-9.
- name: IA-10 - Adaptive Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-10.md
  relation: contains
  description: The family contains control IA-10.
- name: IA-11 - Re-authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-11.md
  relation: contains
  description: The family contains control IA-11.
- name: IA-12 - Identity Proofing
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-12.md
  relation: contains
  description: The family contains control IA-12.
- name: IA-13 - Identity Providers and Authorization Servers
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-13.md
  relation: contains
  description: The family contains control IA-13.
nist_id: IA
base_control_count: 13
control_enhancement_count: 61
---

# Summary

The Identification and Authentication family contains 13 base controls and 61 control enhancements in the NIST OSCAL catalog.

# Controls

- [IA-1 - Policy and Procedures](../controls/ia/ia-1.md) - SP 800-53 control IA-1.
- [IA-2 - Identification and Authentication (Organizational Users)](../controls/ia/ia-2.md) - Uniquely identify and authenticate organizational users and associate that unique identification with processes acting on behalf of those users.
- [IA-3 - Device Identification and Authentication](../controls/ia/ia-3.md) - Uniquely identify and authenticate {{ insert: param, ia-03_odp.01 }} before establishing a {{ insert: param, ia-03_odp.02 }} connection.
- [IA-4 - Identifier Management](../controls/ia/ia-4.md) - Manage system identifiers by:
- [IA-5 - Authenticator Management](../controls/ia/ia-5.md) - Manage system authenticators by:
- [IA-6 - Authentication Feedback](../controls/ia/ia-6.md) - Obscure feedback of authentication information during the authentication process to protect the information from possible exploitation and use by unauthorized individuals.
- [IA-7 - Cryptographic Module Authentication](../controls/ia/ia-7.md) - Implement mechanisms for authentication to a cryptographic module that meet the requirements of applicable laws, executive orders, directives, policies, regulations, standards, and guidelines for such authentication.
- [IA-8 - Identification and Authentication (Non-organizational Users)](../controls/ia/ia-8.md) - Uniquely identify and authenticate non-organizational users or processes acting on behalf of non-organizational users.
- [IA-9 - Service Identification and Authentication](../controls/ia/ia-9.md) - Uniquely identify and authenticate {{ insert: param, ia-09_odp }} before establishing communications with devices, users, or other services or applications.
- [IA-10 - Adaptive Authentication](../controls/ia/ia-10.md) - Require individuals accessing the system to employ {{ insert: param, ia-10_odp.01 }} under specific {{ insert: param, ia-10_odp.02 }}.
- [IA-11 - Re-authentication](../controls/ia/ia-11.md) - Require users to re-authenticate when {{ insert: param, ia-11_odp }}.
- [IA-12 - Identity Proofing](../controls/ia/ia-12.md) - SP 800-53 control IA-12.
- [IA-13 - Identity Providers and Authorization Servers](../controls/ia/ia-13.md) - Employ identity providers and authorization servers to manage user, device, and non-person entity (NPE) identities, attributes, and access rights supporting authentication and authorization decisions in accordance with {

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
