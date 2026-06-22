---
type: control
title: MP-6 - Media Sanitization
description: SP 800-53 control MP-6.
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
- mp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/mp.md
  relation: part_of
  description: MP-6 - Media Sanitization is part of its parent SP 800-53 structure.
- name: MP-6.1 - Review, Approve, Track, Document, and Verify
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-6.1.md
  relation: has_enhancement
  description: MP-6 has enhancement MP-6.1.
- name: MP-6.2 - Equipment Testing
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-6.2.md
  relation: has_enhancement
  description: MP-6 has enhancement MP-6.2.
- name: MP-6.3 - Nondestructive Techniques
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-6.3.md
  relation: has_enhancement
  description: MP-6 has enhancement MP-6.3.
- name: MP-6.4 - Controlled Unclassified Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-6.4.md
  relation: has_enhancement
  description: MP-6 has enhancement MP-6.4.
- name: MP-6.5 - Classified Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-6.5.md
  relation: has_enhancement
  description: MP-6 has enhancement MP-6.5.
- name: MP-6.6 - Media Destruction
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-6.6.md
  relation: has_enhancement
  description: MP-6 has enhancement MP-6.6.
- name: MP-6.7 - Dual Authorization
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-6.7.md
  relation: has_enhancement
  description: MP-6 has enhancement MP-6.7.
- name: MP-6.8 - Remote Purging or Wiping of Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-6.8.md
  relation: has_enhancement
  description: MP-6 has enhancement MP-6.8.
nist_id: MP-6
sort_id: mp-06
implementation_level: organization
parameter_ids:
- mp-6_prm_1
- mp-6_prm_2
- mp-06_odp.01
- mp-06_odp.02
- mp-06_odp.03
- mp-06_odp.04
- mp-06_odp.05
- mp-06_odp.06
reference_links:
- '#91f992fb-f668-4c91-a50f-0f05b95ccee3'
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#c28ae9a8-1121-42a9-a85e-00cfcc9b9a94'
- '#628d22a1-6a11-4784-bc59-5cd9497b5445'
- '#e72fde0b-6fc2-497e-a9db-d8fce5a11b8a'
- '#9be5d661-421f-41ad-854e-86f98b811891'
- '#a5b1d18d-e670-4586-9e6d-4a88b7ba3df6'
- '#0f66be67-85e7-4ca6-bd19-39453e9f4394'
- '#4c501da5-9d79-4cb6-ba80-97260e1ce327'
- '#df9f87e9-71e7-4c74-9ac3-3cabd4e92f21'
- '#ac-3'
- '#ac-7'
- '#au-11'
- '#ma-2'
- '#ma-3'
- '#ma-4'
- '#ma-5'
- '#pm-22'
- '#si-12'
- '#si-18'
- '#si-19'
- '#sr-11'
---

# Summary

SP 800-53 control MP-6.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Media sanitization applies to all digital and non-digital system media subject to disposal or reuse, whether or not the media is considered removable. Examples include digital media in scanners, copiers, printers, notebook computers, workstations, network components, mobile devices, and non-digital media (e.g., paper and microfilm). The sanitization process removes information from system media such that the information cannot be retrieved or reconstructed. Sanitization techniques—including clearing, purging, cryptographic erase, de-identification of personally identifiable information, and destruction—prevent the disclosure of information to unauthorized individuals when such media is reused or released for disposal. Organizations determine the appropriate sanitization methods, recognizing that destruction is sometimes necessary when other methods cannot be applied to media requiring sanitization. Organizations use discretion on the employment of approved sanitization techniques and procedures for media that contains information deemed to be in the public domain or publicly releasable or information deemed to have no adverse impact on organizations or individuals if released for reuse or disposal. Sanitization of non-digital media includes destruction, removing a classified appendix from an otherwise unclassified document, or redacting selected sections or words from a document by obscuring the redacted sections or words in a manner equivalent in effectiveness to removing them from the document. NSA standards and policies control the sanitization process for media that contains classified information. NARA policies control the sanitization process for controlled unclassified information.

# Parameters

- `mp-6_prm_1`
- `mp-6_prm_2`
- `mp-06_odp.01`
- `mp-06_odp.02`
- `mp-06_odp.03`
- `mp-06_odp.04`
- `mp-06_odp.05`
- `mp-06_odp.06`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
