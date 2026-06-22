---
type: control
title: MP-2 - Media Access
description: 'Restrict access to {{ insert: param, mp-2_prm_1 }} to {{ insert: param, mp-2_prm_2 }}.'
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
  description: MP-2 - Media Access is part of its parent SP 800-53 structure.
- name: MP-2.1 - Automated Restricted Access
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-2.1.md
  relation: has_enhancement
  description: MP-2 has enhancement MP-2.1.
- name: MP-2.2 - Cryptographic Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-2.2.md
  relation: has_enhancement
  description: MP-2 has enhancement MP-2.2.
nist_id: MP-2
sort_id: mp-02
implementation_level: organization
parameter_ids:
- mp-2_prm_1
- mp-2_prm_2
- mp-02_odp.01
- mp-02_odp.02
- mp-02_odp.03
- mp-02_odp.04
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#628d22a1-6a11-4784-bc59-5cd9497b5445'
- '#22f2d4f0-4365-4e88-a30d-275c1f5473ea'
- '#ac-19'
- '#au-9'
- '#cp-2'
- '#cp-9'
- '#cp-10'
- '#ma-5'
- '#mp-4'
- '#mp-6'
- '#pe-2'
- '#pe-3'
- '#sc-12'
- '#sc-13'
- '#sc-34'
- '#si-12'
---

# Summary

Restrict access to {{ insert: param, mp-2_prm_1 }} to {{ insert: param, mp-2_prm_2 }}.

# Statement

Restrict access to {{ insert: param, mp-2_prm_1 }} to {{ insert: param, mp-2_prm_2 }}.

# Guidance

System media includes digital and non-digital media. Digital media includes flash drives, diskettes, magnetic tapes, external or removable hard disk drives (e.g., solid state, magnetic), compact discs, and digital versatile discs. Non-digital media includes paper and microfilm. Denying access to patient medical records in a community hospital unless the individuals seeking access to such records are authorized healthcare providers is an example of restricting access to non-digital media. Limiting access to the design specifications stored on compact discs in the media library to individuals on the system development team is an example of restricting access to digital media.

# Parameters

- `mp-2_prm_1`
- `mp-2_prm_2`
- `mp-02_odp.01`
- `mp-02_odp.02`
- `mp-02_odp.03`
- `mp-02_odp.04`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
