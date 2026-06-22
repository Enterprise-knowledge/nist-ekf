---
type: control
title: IA-8 - Identification and Authentication (Non-organizational Users)
description: Uniquely identify and authenticate non-organizational users or processes acting on behalf of non-organizational
  users.
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
  description: IA-8 - Identification and Authentication (Non-organizational Users) is part of its parent SP 800-53
    structure.
- name: IA-8.1 - Acceptance of PIV Credentials from Other Agencies
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-8.1.md
  relation: has_enhancement
  description: IA-8 has enhancement IA-8.1.
- name: IA-8.2 - Acceptance of External Authenticators
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-8.2.md
  relation: has_enhancement
  description: IA-8 has enhancement IA-8.2.
- name: IA-8.3 - Use of FICAM-approved Products
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-8.3.md
  relation: has_enhancement
  description: IA-8 has enhancement IA-8.3.
- name: IA-8.4 - Use of Defined Profiles
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-8.4.md
  relation: has_enhancement
  description: IA-8 has enhancement IA-8.4.
- name: IA-8.5 - Acceptance of PIV-I Credentials
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-8.5.md
  relation: has_enhancement
  description: IA-8 has enhancement IA-8.5.
- name: IA-8.6 - Disassociability
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-8.6.md
  relation: has_enhancement
  description: IA-8 has enhancement IA-8.6.
nist_id: IA-8
sort_id: ia-08
implementation_level: system
parameter_ids: []
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#a1555677-2b9d-4868-a97b-a1363aff32f5'
- '#7ba1d91c-3934-4d5a-8532-b32f864ad34c'
- '#737513fa-6758-403f-831d-5ddab5e23cb3'
- '#10963761-58fc-4b20-b3d6-b44a54daba03'
- '#2100332a-16a5-4598-bacf-7261baea9711'
- '#98d415ca-7281-4064-9931-0c366637e324'
- '#ac-2'
- '#ac-6'
- '#ac-14'
- '#ac-17'
- '#ac-18'
- '#au-6'
- '#ia-2'
- '#ia-4'
- '#ia-5'
- '#ia-10'
- '#ia-11'
- '#ia-13'
- '#ma-4'
- '#ra-3'
- '#sa-4'
- '#sc-8'
---

# Summary

Uniquely identify and authenticate non-organizational users or processes acting on behalf of non-organizational users.

# Statement

Uniquely identify and authenticate non-organizational users or processes acting on behalf of non-organizational users.

# Guidance

Non-organizational users include system users other than organizational users explicitly covered by [IA-2](#ia-2) . Non-organizational users are uniquely identified and authenticated for accesses other than those explicitly identified and documented in [AC-14](#ac-14) . Identification and authentication of non-organizational users accessing federal systems may be required to protect federal, proprietary, or privacy-related information (with exceptions noted for national security systems). Organizations consider many factors—including security, privacy, scalability, and practicality—when balancing the need to ensure ease of use for access to federal information and systems with the need to protect and adequately mitigate risk.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
