---
type: control_family
title: AC - Access Control
description: SP 800-53 control family for Access Control.
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
- name: The Controls
  path: /bundles/nist-sp-800-53-r5/knowledge/sections/controls.md
  relation: part_of
  description: This family is part of the controls section.
- name: AC-1 - Policy and Procedures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-1.md
  relation: contains
  description: The family contains control AC-1.
- name: AC-2 - Account Management
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-2.md
  relation: contains
  description: The family contains control AC-2.
- name: AC-3 - Access Enforcement
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-3.md
  relation: contains
  description: The family contains control AC-3.
- name: AC-4 - Information Flow Enforcement
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-4.md
  relation: contains
  description: The family contains control AC-4.
- name: AC-5 - Separation of Duties
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-5.md
  relation: contains
  description: The family contains control AC-5.
- name: AC-6 - Least Privilege
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-6.md
  relation: contains
  description: The family contains control AC-6.
- name: AC-7 - Unsuccessful Logon Attempts
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-7.md
  relation: contains
  description: The family contains control AC-7.
- name: AC-8 - System Use Notification
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-8.md
  relation: contains
  description: The family contains control AC-8.
- name: AC-9 - Previous Logon Notification
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-9.md
  relation: contains
  description: The family contains control AC-9.
- name: AC-10 - Concurrent Session Control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-10.md
  relation: contains
  description: The family contains control AC-10.
- name: AC-11 - Device Lock
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-11.md
  relation: contains
  description: The family contains control AC-11.
- name: AC-12 - Session Termination
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-12.md
  relation: contains
  description: The family contains control AC-12.
- name: AC-13 - Supervision and Review — Access Control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-13.md
  relation: contains
  description: The family contains control AC-13.
- name: AC-14 - Permitted Actions Without Identification or Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-14.md
  relation: contains
  description: The family contains control AC-14.
- name: AC-15 - Automated Marking
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-15.md
  relation: contains
  description: The family contains control AC-15.
- name: AC-16 - Security and Privacy Attributes
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-16.md
  relation: contains
  description: The family contains control AC-16.
- name: AC-17 - Remote Access
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-17.md
  relation: contains
  description: The family contains control AC-17.
- name: AC-18 - Wireless Access
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-18.md
  relation: contains
  description: The family contains control AC-18.
- name: AC-19 - Access Control for Mobile Devices
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-19.md
  relation: contains
  description: The family contains control AC-19.
- name: AC-20 - Use of External Systems
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-20.md
  relation: contains
  description: The family contains control AC-20.
- name: AC-21 - Information Sharing
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-21.md
  relation: contains
  description: The family contains control AC-21.
- name: AC-22 - Publicly Accessible Content
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-22.md
  relation: contains
  description: The family contains control AC-22.
- name: AC-23 - Data Mining Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-23.md
  relation: contains
  description: The family contains control AC-23.
- name: AC-24 - Access Control Decisions
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-24.md
  relation: contains
  description: The family contains control AC-24.
- name: AC-25 - Reference Monitor
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-25.md
  relation: contains
  description: The family contains control AC-25.
nist_id: AC
base_control_count: 25
control_enhancement_count: 122
---

# Summary

The Access Control family contains 25 base controls and 122 control enhancements in the NIST OSCAL catalog.

# Controls

- [AC-1 - Policy and Procedures](../controls/ac/ac-1.md) - SP 800-53 control AC-1.
- [AC-2 - Account Management](../controls/ac/ac-2.md) - SP 800-53 control AC-2.
- [AC-3 - Access Enforcement](../controls/ac/ac-3.md) - Enforce approved authorizations for logical access to information and system resources in accordance with applicable access control policies.
- [AC-4 - Information Flow Enforcement](../controls/ac/ac-4.md) - Enforce approved authorizations for controlling the flow of information within the system and between connected systems based on {{ insert: param, ac-04_odp }}.
- [AC-5 - Separation of Duties](../controls/ac/ac-5.md) - SP 800-53 control AC-5.
- [AC-6 - Least Privilege](../controls/ac/ac-6.md) - Employ the principle of least privilege, allowing only authorized accesses for users (or processes acting on behalf of users) that are necessary to accomplish assigned organizational tasks.
- [AC-7 - Unsuccessful Logon Attempts](../controls/ac/ac-7.md) - SP 800-53 control AC-7.
- [AC-8 - System Use Notification](../controls/ac/ac-8.md) - SP 800-53 control AC-8.
- [AC-9 - Previous Logon Notification](../controls/ac/ac-9.md) - Notify the user, upon successful logon to the system, of the date and time of the last logon.
- [AC-10 - Concurrent Session Control](../controls/ac/ac-10.md) - Limit the number of concurrent sessions for each {{ insert: param, ac-10_odp.01 }} to {{ insert: param, ac-10_odp.02 }}.
- [AC-11 - Device Lock](../controls/ac/ac-11.md) - SP 800-53 control AC-11.
- [AC-12 - Session Termination](../controls/ac/ac-12.md) - Automatically terminate a user session after {{ insert: param, ac-12_odp }}.
- [AC-13 - Supervision and Review — Access Control](../controls/ac/ac-13.md) - SP 800-53 control AC-13.
- [AC-14 - Permitted Actions Without Identification or Authentication](../controls/ac/ac-14.md) - SP 800-53 control AC-14.
- [AC-15 - Automated Marking](../controls/ac/ac-15.md) - SP 800-53 control AC-15.
- [AC-16 - Security and Privacy Attributes](../controls/ac/ac-16.md) - SP 800-53 control AC-16.
- [AC-17 - Remote Access](../controls/ac/ac-17.md) - SP 800-53 control AC-17.
- [AC-18 - Wireless Access](../controls/ac/ac-18.md) - SP 800-53 control AC-18.
- [AC-19 - Access Control for Mobile Devices](../controls/ac/ac-19.md) - SP 800-53 control AC-19.
- [AC-20 - Use of External Systems](../controls/ac/ac-20.md) - SP 800-53 control AC-20.
- [AC-21 - Information Sharing](../controls/ac/ac-21.md) - SP 800-53 control AC-21.
- [AC-22 - Publicly Accessible Content](../controls/ac/ac-22.md) - SP 800-53 control AC-22.
- [AC-23 - Data Mining Protection](../controls/ac/ac-23.md) - Employ {{ insert: param, ac-23_odp.01 }} for {{ insert: param, ac-23_odp.02 }} to detect and protect against unauthorized data mining.
- [AC-24 - Access Control Decisions](../controls/ac/ac-24.md) - {{ insert: param, ac-24_odp.01 }} to ensure {{ insert: param, ac-24_odp.02 }} are applied to each access request prior to access enforcement.
- [AC-25 - Reference Monitor](../controls/ac/ac-25.md) - Implement a reference monitor for {{ insert: param, ac-25_odp }} that is tamperproof, always invoked, and small enough to be subject to analysis and testing, the completeness of which can be assured.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
