---
type: control
title: CM-5 - Access Restrictions for Change
description: Define, document, approve, and enforce physical and logical access restrictions associated with changes
  to the system.
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
- cm
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/cm.md
  relation: part_of
  description: CM-5 - Access Restrictions for Change is part of its parent SP 800-53 structure.
- name: CM-5.1 - Automated Access Enforcement and Audit Records
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-5.1.md
  relation: has_enhancement
  description: CM-5 has enhancement CM-5.1.
- name: CM-5.2 - Review System Changes
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-5.2.md
  relation: has_enhancement
  description: CM-5 has enhancement CM-5.2.
- name: CM-5.3 - Signed Components
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-5.3.md
  relation: has_enhancement
  description: CM-5 has enhancement CM-5.3.
- name: CM-5.4 - Dual Authorization
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-5.4.md
  relation: has_enhancement
  description: CM-5 has enhancement CM-5.4.
- name: CM-5.5 - Privilege Limitation for Production and Operation
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-5.5.md
  relation: has_enhancement
  description: CM-5 has enhancement CM-5.5.
- name: CM-5.6 - Limit Library Privileges
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-5.6.md
  relation: has_enhancement
  description: CM-5 has enhancement CM-5.6.
- name: CM-5.7 - Automatic Implementation of Security Safeguards
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-5.7.md
  relation: has_enhancement
  description: CM-5 has enhancement CM-5.7.
nist_id: CM-5
sort_id: cm-05
implementation_level: organization
parameter_ids: []
reference_links:
- '#678e3d6c-150b-4393-aec5-6e3481eb1e00'
- '#7c37a38d-21d7-40d8-bc3d-b5e27eac17e1'
- '#ac-3'
- '#ac-5'
- '#ac-6'
- '#cm-9'
- '#pe-3'
- '#sc-28'
- '#sc-34'
- '#sc-37'
- '#si-2'
- '#si-10'
---

# Summary

Define, document, approve, and enforce physical and logical access restrictions associated with changes to the system.

# Statement

Define, document, approve, and enforce physical and logical access restrictions associated with changes to the system.

# Guidance

Changes to the hardware, software, or firmware components of systems or the operational procedures related to the system can potentially have significant effects on the security of the systems or individuals’ privacy. Therefore, organizations permit only qualified and authorized individuals to access systems for purposes of initiating changes. Access restrictions include physical and logical access controls (see [AC-3](#ac-3) and [PE-3](#pe-3) ), software libraries, workflow automation, media libraries, abstract layers (i.e., changes implemented into external interfaces rather than directly into systems), and change windows (i.e., changes occur only during specified times).

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
