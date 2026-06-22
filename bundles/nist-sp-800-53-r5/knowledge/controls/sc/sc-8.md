---
type: control
title: SC-8 - Transmission Confidentiality and Integrity
description: 'Protect the {{ insert: param, sc-08_odp }} of transmitted information.'
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
- sc
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/sc.md
  relation: part_of
  description: SC-8 - Transmission Confidentiality and Integrity is part of its parent SP 800-53 structure.
- name: SC-8.1 - Cryptographic Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-8.1.md
  relation: has_enhancement
  description: SC-8 has enhancement SC-8.1.
- name: SC-8.2 - Pre- and Post-transmission Handling
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-8.2.md
  relation: has_enhancement
  description: SC-8 has enhancement SC-8.2.
- name: SC-8.3 - Cryptographic Protection for Message Externals
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-8.3.md
  relation: has_enhancement
  description: SC-8 has enhancement SC-8.3.
- name: SC-8.4 - Conceal or Randomize Communications
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-8.4.md
  relation: has_enhancement
  description: SC-8 has enhancement SC-8.4.
- name: SC-8.5 - Protected Distribution System
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-8.5.md
  relation: has_enhancement
  description: SC-8 has enhancement SC-8.5.
nist_id: SC-8
sort_id: sc-08
implementation_level: system
parameter_ids:
- sc-08_odp
reference_links:
- '#678e3d6c-150b-4393-aec5-6e3481eb1e00'
- '#736d6310-e403-4b57-a79d-9967970c66d7'
- '#7537638e-2837-407d-844b-40fb3fafdd99'
- '#d4d7c760-2907-403b-8b2a-767ca5370ecd'
- '#fe209006-bfd4-4033-a79a-9fee1adaf372'
- '#6bc4d137-aece-42a8-8081-9ecb1ebe9fb4'
- '#1c71b420-2bd9-4e52-9fc8-390f58b85b59'
- '#4c501da5-9d79-4cb6-ba80-97260e1ce327'
- '#ac-17'
- '#ac-18'
- '#au-10'
- '#ia-3'
- '#ia-8'
- '#ia-9'
- '#ma-4'
- '#pe-4'
- '#sa-4'
- '#sa-8'
- '#sc-7'
- '#sc-16'
- '#sc-20'
- '#sc-23'
- '#sc-28'
---

# Summary

Protect the {{ insert: param, sc-08_odp }} of transmitted information.

# Statement

Protect the {{ insert: param, sc-08_odp }} of transmitted information.

# Guidance

Protecting the confidentiality and integrity of transmitted information applies to internal and external networks as well as any system components that can transmit information, including servers, notebook computers, desktop computers, mobile devices, printers, copiers, scanners, facsimile machines, and radios. Unprotected communication paths are exposed to the possibility of interception and modification. Protecting the confidentiality and integrity of information can be accomplished by physical or logical means. Physical protection can be achieved by using protected distribution systems. A protected distribution system is a wireline or fiber-optics telecommunications system that includes terminals and adequate electromagnetic, acoustical, electrical, and physical controls to permit its use for the unencrypted transmission of classified information. Logical protection can be achieved by employing encryption techniques.

Organizations that rely on commercial providers who offer transmission services as commodity services rather than as fully dedicated services may find it difficult to obtain the necessary assurances regarding the implementation of needed controls for transmission confidentiality and integrity. In such situations, organizations determine what types of confidentiality or integrity services are available in standard, commercial telecommunications service packages. If it is not feasible to obtain the necessary controls and assurances of control effectiveness through appropriate contracting vehicles, organizations can implement appropriate compensating controls.

# Parameters

- `sc-08_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
