---
type: control
title: PS-3 - Personnel Screening
description: SP 800-53 control PS-3.
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
- ps
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ps.md
  relation: part_of
  description: PS-3 - Personnel Screening is part of its parent SP 800-53 structure.
- name: PS-3.1 - Classified Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ps/ps-3.1.md
  relation: has_enhancement
  description: PS-3 has enhancement PS-3.1.
- name: PS-3.2 - Formal Indoctrination
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ps/ps-3.2.md
  relation: has_enhancement
  description: PS-3 has enhancement PS-3.2.
- name: PS-3.3 - Information Requiring Special Protective Measures
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ps/ps-3.3.md
  relation: has_enhancement
  description: PS-3 has enhancement PS-3.3.
- name: PS-3.4 - Citizenship Requirements
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ps/ps-3.4.md
  relation: has_enhancement
  description: PS-3 has enhancement PS-3.4.
nist_id: PS-3
sort_id: ps-03
implementation_level: organization
parameter_ids:
- ps-3_prm_1
- ps-03_odp.01
- ps-03_odp.02
reference_links:
- '#55b0c93a-5e48-457a-baa6-5ce81c239c49'
- '#0af071a6-cf8e-48ee-8c82-fe91efa20f94'
- '#628d22a1-6a11-4784-bc59-5cd9497b5445'
- '#7ba1d91c-3934-4d5a-8532-b32f864ad34c'
- '#e72fde0b-6fc2-497e-a9db-d8fce5a11b8a'
- '#9be5d661-421f-41ad-854e-86f98b811891'
- '#858705be-3c1f-48aa-a328-0ce398d95ef0'
- '#7af2e6ec-9f7e-4232-ad3f-09888eb0793a'
- '#828856bd-d7c4-427b-8b51-815517ec382d'
- '#ac-2'
- '#ia-4'
- '#ma-5'
- '#pe-2'
- '#pm-12'
- '#ps-2'
- '#ps-6'
- '#ps-7'
- '#sa-21'
---

# Summary

SP 800-53 control PS-3.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Personnel screening and rescreening activities reflect applicable laws, executive orders, directives, regulations, policies, standards, guidelines, and specific criteria established for the risk designations of assigned positions. Examples of personnel screening include background investigations and agency checks. Organizations may define different rescreening conditions and frequencies for personnel accessing systems based on types of information processed, stored, or transmitted by the systems.

# Parameters

- `ps-3_prm_1`
- `ps-03_odp.01`
- `ps-03_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
