---
type: control
title: MP-5 - Media Transport
description: SP 800-53 control MP-5.
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
  description: MP-5 - Media Transport is part of its parent SP 800-53 structure.
- name: MP-5.1 - Protection Outside of Controlled Areas
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-5.1.md
  relation: has_enhancement
  description: MP-5 has enhancement MP-5.1.
- name: MP-5.2 - Documentation of Activities
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-5.2.md
  relation: has_enhancement
  description: MP-5 has enhancement MP-5.2.
- name: MP-5.3 - Custodians
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-5.3.md
  relation: has_enhancement
  description: MP-5 has enhancement MP-5.3.
- name: MP-5.4 - Cryptographic Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-5.4.md
  relation: has_enhancement
  description: MP-5 has enhancement MP-5.4.
nist_id: MP-5
sort_id: mp-05
implementation_level: organization
parameter_ids:
- mp-5_prm_2
- mp-05_odp.01
- mp-05_odp.02
- mp-05_odp.03
reference_links:
- '#628d22a1-6a11-4784-bc59-5cd9497b5445'
- '#e72fde0b-6fc2-497e-a9db-d8fce5a11b8a'
- '#9be5d661-421f-41ad-854e-86f98b811891'
- '#ac-7'
- '#ac-19'
- '#cp-2'
- '#cp-9'
- '#mp-3'
- '#mp-4'
- '#pe-16'
- '#pl-2'
- '#sc-12'
- '#sc-13'
- '#sc-28'
- '#sc-34'
---

# Summary

SP 800-53 control MP-5.

# Statement

No statement text was present in the OSCAL record.

# Guidance

System media includes digital and non-digital media. Digital media includes flash drives, diskettes, magnetic tapes, external or removable hard disk drives (e.g., solid state and magnetic), compact discs, and digital versatile discs. Non-digital media includes microfilm and paper. Controlled areas are spaces for which organizations provide physical or procedural controls to meet requirements established for protecting information and systems. Controls to protect media during transport include cryptography and locked containers. Cryptographic mechanisms can provide confidentiality and integrity protections depending on the mechanisms implemented. Activities associated with media transport include releasing media for transport, ensuring that media enters the appropriate transport processes, and the actual transport. Authorized transport and courier personnel may include individuals external to the organization. Maintaining accountability of media during transport includes restricting transport activities to authorized personnel and tracking and/or obtaining records of transport activities as the media moves through the transportation system to prevent and detect loss, destruction, or tampering. Organizations establish documentation requirements for activities associated with the transport of system media in accordance with organizational assessments of risk. Organizations maintain the flexibility to define record-keeping methods for the different types of media transport as part of a system of transport-related records.

# Parameters

- `mp-5_prm_2`
- `mp-05_odp.01`
- `mp-05_odp.02`
- `mp-05_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
