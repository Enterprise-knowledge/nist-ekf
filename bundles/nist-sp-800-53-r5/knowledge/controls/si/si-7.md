---
type: control
title: SI-7 - Software, Firmware, and Information Integrity
description: SP 800-53 control SI-7.
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
- si
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/si.md
  relation: part_of
  description: SI-7 - Software, Firmware, and Information Integrity is part of its parent SP 800-53 structure.
- name: SI-7.1 - Integrity Checks
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-7.1.md
  relation: has_enhancement
  description: SI-7 has enhancement SI-7.1.
- name: SI-7.2 - Automated Notifications of Integrity Violations
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-7.2.md
  relation: has_enhancement
  description: SI-7 has enhancement SI-7.2.
- name: SI-7.3 - Centrally Managed Integrity Tools
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-7.3.md
  relation: has_enhancement
  description: SI-7 has enhancement SI-7.3.
- name: SI-7.4 - Tamper-evident Packaging
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-7.4.md
  relation: has_enhancement
  description: SI-7 has enhancement SI-7.4.
- name: SI-7.5 - Automated Response to Integrity Violations
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-7.5.md
  relation: has_enhancement
  description: SI-7 has enhancement SI-7.5.
- name: SI-7.6 - Cryptographic Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-7.6.md
  relation: has_enhancement
  description: SI-7 has enhancement SI-7.6.
- name: SI-7.7 - Integration of Detection and Response
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-7.7.md
  relation: has_enhancement
  description: SI-7 has enhancement SI-7.7.
- name: SI-7.8 - Auditing Capability for Significant Events
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-7.8.md
  relation: has_enhancement
  description: SI-7 has enhancement SI-7.8.
- name: SI-7.9 - Verify Boot Process
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-7.9.md
  relation: has_enhancement
  description: SI-7 has enhancement SI-7.9.
- name: SI-7.10 - Protection of Boot Firmware
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-7.10.md
  relation: has_enhancement
  description: SI-7 has enhancement SI-7.10.
- name: SI-7.11 - Confined Environments with Limited Privileges
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-7.11.md
  relation: has_enhancement
  description: SI-7 has enhancement SI-7.11.
- name: SI-7.12 - Integrity Verification
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-7.12.md
  relation: has_enhancement
  description: SI-7 has enhancement SI-7.12.
- name: SI-7.13 - Code Execution in Protected Environments
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-7.13.md
  relation: has_enhancement
  description: SI-7 has enhancement SI-7.13.
- name: SI-7.14 - Binary or Machine Executable Code
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-7.14.md
  relation: has_enhancement
  description: SI-7 has enhancement SI-7.14.
- name: SI-7.15 - Code Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-7.15.md
  relation: has_enhancement
  description: SI-7 has enhancement SI-7.15.
- name: SI-7.16 - Time Limit on Process Execution Without Supervision
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-7.16.md
  relation: has_enhancement
  description: SI-7 has enhancement SI-7.16.
- name: SI-7.17 - Runtime Application Self-protection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-7.17.md
  relation: has_enhancement
  description: SI-7 has enhancement SI-7.17.
nist_id: SI-7
sort_id: si-07
implementation_level: organization
parameter_ids:
- si-7_prm_1
- si-7_prm_2
- si-07_odp.01
- si-07_odp.02
- si-07_odp.03
- si-07_odp.04
- si-07_odp.05
- si-07_odp.06
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#678e3d6c-150b-4393-aec5-6e3481eb1e00'
- '#eea3c092-42ed-4382-a6f4-1adadef01b9d'
- '#7c37a38d-21d7-40d8-bc3d-b5e27eac17e1'
- '#a295ca19-8c75-4b4c-8800-98024732e181'
- '#4895b4cd-34c5-4667-bf8a-27d443c12047'
- '#e47ee630-9cbc-4133-880e-e013f83ccd51'
- '#ac-4'
- '#cm-3'
- '#cm-7'
- '#cm-8'
- '#ma-3'
- '#ma-4'
- '#ra-5'
- '#sa-8'
- '#sa-9'
- '#sa-10'
- '#sc-8'
- '#sc-12'
- '#sc-13'
- '#sc-28'
- '#sc-37'
- '#si-3'
- '#sr-3'
- '#sr-4'
- '#sr-5'
- '#sr-6'
- '#sr-9'
- '#sr-10'
- '#sr-11'
---

# Summary

SP 800-53 control SI-7.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Unauthorized changes to software, firmware, and information can occur due to errors or malicious activity. Software includes operating systems (with key internal components, such as kernels or drivers), middleware, and applications. Firmware interfaces include Unified Extensible Firmware Interface (UEFI) and Basic Input/Output System (BIOS). Information includes personally identifiable information and metadata that contains security and privacy attributes associated with information. Integrity-checking mechanisms—including parity checks, cyclical redundancy checks, cryptographic hashes, and associated tools—can automatically monitor the integrity of systems and hosted applications.

# Parameters

- `si-7_prm_1`
- `si-7_prm_2`
- `si-07_odp.01`
- `si-07_odp.02`
- `si-07_odp.03`
- `si-07_odp.04`
- `si-07_odp.05`
- `si-07_odp.06`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
