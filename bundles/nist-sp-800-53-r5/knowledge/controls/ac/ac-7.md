---
type: control
title: AC-7 - Unsuccessful Logon Attempts
description: SP 800-53 control AC-7.
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
  description: AC-7 - Unsuccessful Logon Attempts is part of its parent SP 800-53 structure.
- name: AC-7.1 - Automatic Account Lock
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-7.1.md
  relation: has_enhancement
  description: AC-7 has enhancement AC-7.1.
- name: AC-7.2 - Purge or Wipe Mobile Device
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-7.2.md
  relation: has_enhancement
  description: AC-7 has enhancement AC-7.2.
- name: AC-7.3 - Biometric Attempt Limiting
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-7.3.md
  relation: has_enhancement
  description: AC-7 has enhancement AC-7.3.
- name: AC-7.4 - Use of Alternate Authentication Factor
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-7.4.md
  relation: has_enhancement
  description: AC-7 has enhancement AC-7.4.
nist_id: AC-7
sort_id: ac-07
implementation_level: system
parameter_ids:
- ac-07_odp.01
- ac-07_odp.02
- ac-07_odp.03
- ac-07_odp.04
- ac-07_odp.05
- ac-07_odp.06
reference_links:
- '#737513fa-6758-403f-831d-5ddab5e23cb3'
- '#0f66be67-85e7-4ca6-bd19-39453e9f4394'
- '#ac-2'
- '#ac-9'
- '#au-2'
- '#au-6'
- '#ia-5'
---

# Summary

SP 800-53 control AC-7.

# Statement

No statement text was present in the OSCAL record.

# Guidance

The need to limit unsuccessful logon attempts and take subsequent action when the maximum number of attempts is exceeded applies regardless of whether the logon occurs via a local or network connection. Due to the potential for denial of service, automatic lockouts initiated by systems are usually temporary and automatically release after a predetermined, organization-defined time period. If a delay algorithm is selected, organizations may employ different algorithms for different components of the system based on the capabilities of those components. Responses to unsuccessful logon attempts may be implemented at the operating system and the application levels. Organization-defined actions that may be taken when the number of allowed consecutive invalid logon attempts is exceeded include prompting the user to answer a secret question in addition to the username and password, invoking a lockdown mode with limited user capabilities (instead of full lockout), allowing users to only logon from specified Internet Protocol (IP) addresses, requiring a CAPTCHA to prevent automated attacks, or applying user profiles such as location, time of day, IP address, device, or Media Access Control (MAC) address. If automatic system lockout or execution of a delay algorithm is not implemented in support of the availability objective, organizations consider a combination of other actions to help prevent brute force attacks. In addition to the above, organizations can prompt users to respond to a secret question before the number of allowed unsuccessful logon attempts is exceeded. Automatically unlocking an account after a specified period of time is generally not permitted. However, exceptions may be required based on operational mission or need.

# Parameters

- `ac-07_odp.01`
- `ac-07_odp.02`
- `ac-07_odp.03`
- `ac-07_odp.04`
- `ac-07_odp.05`
- `ac-07_odp.06`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
