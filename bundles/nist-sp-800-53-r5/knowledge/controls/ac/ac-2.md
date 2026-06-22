---
type: control
title: AC-2 - Account Management
description: SP 800-53 control AC-2.
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
  description: AC-2 - Account Management is part of its parent SP 800-53 structure.
- name: AC-2.1 - Automated System Account Management
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-2.1.md
  relation: has_enhancement
  description: AC-2 has enhancement AC-2.1.
- name: AC-2.2 - Automated Temporary and Emergency Account Management
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-2.2.md
  relation: has_enhancement
  description: AC-2 has enhancement AC-2.2.
- name: AC-2.3 - Disable Accounts
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-2.3.md
  relation: has_enhancement
  description: AC-2 has enhancement AC-2.3.
- name: AC-2.4 - Automated Audit Actions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-2.4.md
  relation: has_enhancement
  description: AC-2 has enhancement AC-2.4.
- name: AC-2.5 - Inactivity Logout
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-2.5.md
  relation: has_enhancement
  description: AC-2 has enhancement AC-2.5.
- name: AC-2.6 - Dynamic Privilege Management
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-2.6.md
  relation: has_enhancement
  description: AC-2 has enhancement AC-2.6.
- name: AC-2.7 - Privileged User Accounts
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-2.7.md
  relation: has_enhancement
  description: AC-2 has enhancement AC-2.7.
- name: AC-2.8 - Dynamic Account Management
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-2.8.md
  relation: has_enhancement
  description: AC-2 has enhancement AC-2.8.
- name: AC-2.9 - Restrictions on Use of Shared and Group Accounts
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-2.9.md
  relation: has_enhancement
  description: AC-2 has enhancement AC-2.9.
- name: AC-2.10 - Shared and Group Account Credential Change
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-2.10.md
  relation: has_enhancement
  description: AC-2 has enhancement AC-2.10.
- name: AC-2.11 - Usage Conditions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-2.11.md
  relation: has_enhancement
  description: AC-2 has enhancement AC-2.11.
- name: AC-2.12 - Account Monitoring for Atypical Usage
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-2.12.md
  relation: has_enhancement
  description: AC-2 has enhancement AC-2.12.
- name: AC-2.13 - Disable Accounts for High-risk Individuals
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-2.13.md
  relation: has_enhancement
  description: AC-2 has enhancement AC-2.13.
nist_id: AC-2
sort_id: ac-02
implementation_level: organization
parameter_ids:
- ac-02_odp.01
- ac-02_odp.02
- ac-02_odp.03
- ac-02_odp.04
- ac-02_odp.05
- ac-02_odp.06
- ac-02_odp.07
- ac-02_odp.08
- ac-02_odp.09
- ac-02_odp.10
reference_links:
- '#2956e175-f674-43f4-b1b9-e074ad9fc39c'
- '#388a3aa2-5d85-4bad-b8a3-77db80d63c4f'
- '#53df282b-8b3f-483a-bad1-6a8b8ac00114'
- '#ac-3'
- '#ac-5'
- '#ac-6'
- '#ac-17'
- '#ac-18'
- '#ac-20'
- '#ac-24'
- '#au-2'
- '#au-12'
- '#cm-5'
- '#ia-2'
- '#ia-4'
- '#ia-5'
- '#ia-8'
- '#ma-3'
- '#ma-5'
- '#pe-2'
- '#pl-4'
- '#ps-2'
- '#ps-4'
- '#ps-5'
- '#ps-7'
- '#pt-2'
- '#pt-3'
- '#sc-7'
- '#sc-12'
- '#sc-13'
- '#sc-37'
---

# Summary

SP 800-53 control AC-2.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Examples of system account types include individual, shared, group, system, guest, anonymous, emergency, developer, temporary, and service. Identification of authorized system users and the specification of access privileges reflect the requirements in other controls in the security plan. Users requiring administrative privileges on system accounts receive additional scrutiny by organizational personnel responsible for approving such accounts and privileged access, including system owner, mission or business owner, senior agency information security officer, or senior agency official for privacy. Types of accounts that organizations may wish to prohibit due to increased risk include shared, group, emergency, anonymous, temporary, and guest accounts.

Where access involves personally identifiable information, security programs collaborate with the senior agency official for privacy to establish the specific conditions for group and role membership; specify authorized users, group and role membership, and access authorizations for each account; and create, adjust, or remove system accounts in accordance with organizational policies. Policies can include such information as account expiration dates or other factors that trigger the disabling of accounts. Organizations may choose to define access privileges or other attributes by account, type of account, or a combination of the two. Examples of other attributes required for authorizing access include restrictions on time of day, day of week, and point of origin. In defining other system account attributes, organizations consider system-related requirements and mission/business requirements. Failure to consider these factors could affect system availability.

Temporary and emergency accounts are intended for short-term use. Organizations establish temporary accounts as part of normal account activation procedures when there is a need for short-term accounts without the demand for immediacy in account activation. Organizations establish emergency accounts in response to crisis situations and with the need for rapid account activation. Therefore, emergency account activation may bypass normal account authorization processes. Emergency and temporary accounts are not to be confused with infrequently used accounts, including local logon accounts used for special tasks or when network resources are unavailable (may also be known as accounts of last resort). Such accounts remain available and are not subject to automatic disabling or removal dates. Conditions for disabling or deactivating accounts include when shared/group, emergency, or temporary accounts are no longer required and when individuals are transferred or terminated. Changing shared/group authenticators when members leave the group is intended to ensure that former group members do not retain access to the shared or group account. Some types of system accounts may require specialized training.

# Parameters

- `ac-02_odp.01`
- `ac-02_odp.02`
- `ac-02_odp.03`
- `ac-02_odp.04`
- `ac-02_odp.05`
- `ac-02_odp.06`
- `ac-02_odp.07`
- `ac-02_odp.08`
- `ac-02_odp.09`
- `ac-02_odp.10`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
