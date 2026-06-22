---
type: control
title: AC-9 - Previous Logon Notification
description: Notify the user, upon successful logon to the system, of the date and time of the last logon.
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
  description: AC-9 - Previous Logon Notification is part of its parent SP 800-53 structure.
- name: AC-9.1 - Unsuccessful Logons
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-9.1.md
  relation: has_enhancement
  description: AC-9 has enhancement AC-9.1.
- name: AC-9.2 - Successful and Unsuccessful Logons
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-9.2.md
  relation: has_enhancement
  description: AC-9 has enhancement AC-9.2.
- name: AC-9.3 - Notification of Account Changes
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-9.3.md
  relation: has_enhancement
  description: AC-9 has enhancement AC-9.3.
- name: AC-9.4 - Additional Logon Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-9.4.md
  relation: has_enhancement
  description: AC-9 has enhancement AC-9.4.
nist_id: AC-9
sort_id: ac-09
implementation_level: system
parameter_ids: []
reference_links:
- '#ac-7'
- '#pl-4'
---

# Summary

Notify the user, upon successful logon to the system, of the date and time of the last logon.

# Statement

Notify the user, upon successful logon to the system, of the date and time of the last logon.

# Guidance

Previous logon notification is applicable to system access via human user interfaces and access to systems that occurs in other types of architectures. Information about the last successful logon allows the user to recognize if the date and time provided is not consistent with the user’s last access.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
