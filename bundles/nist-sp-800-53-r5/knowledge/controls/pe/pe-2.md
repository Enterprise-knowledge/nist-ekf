---
type: control
title: PE-2 - Physical Access Authorizations
description: SP 800-53 control PE-2.
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
- pe
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/pe.md
  relation: part_of
  description: PE-2 - Physical Access Authorizations is part of its parent SP 800-53 structure.
- name: PE-2.1 - Access by Position or Role
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-2.1.md
  relation: has_enhancement
  description: PE-2 has enhancement PE-2.1.
- name: PE-2.2 - Two Forms of Identification
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-2.2.md
  relation: has_enhancement
  description: PE-2 has enhancement PE-2.2.
- name: PE-2.3 - Restrict Unescorted Access
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-2.3.md
  relation: has_enhancement
  description: PE-2 has enhancement PE-2.3.
nist_id: PE-2
sort_id: pe-02
implementation_level: organization
parameter_ids:
- pe-02_odp
reference_links:
- '#7ba1d91c-3934-4d5a-8532-b32f864ad34c'
- '#858705be-3c1f-48aa-a328-0ce398d95ef0'
- '#7af2e6ec-9f7e-4232-ad3f-09888eb0793a'
- '#828856bd-d7c4-427b-8b51-815517ec382d'
- '#at-3'
- '#au-9'
- '#ia-4'
- '#ma-5'
- '#mp-2'
- '#pe-3'
- '#pe-4'
- '#pe-5'
- '#pe-8'
- '#pm-12'
- '#ps-3'
- '#ps-4'
- '#ps-5'
- '#ps-6'
---

# Summary

SP 800-53 control PE-2.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Physical access authorizations apply to employees and visitors. Individuals with permanent physical access authorization credentials are not considered visitors. Authorization credentials include ID badges, identification cards, and smart cards. Organizations determine the strength of authorization credentials needed consistent with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines. Physical access authorizations may not be necessary to access certain areas within facilities that are designated as publicly accessible.

# Parameters

- `pe-02_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
