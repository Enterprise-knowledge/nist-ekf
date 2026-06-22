---
type: control
title: PS-6 - Access Agreements
description: SP 800-53 control PS-6.
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
  description: PS-6 - Access Agreements is part of its parent SP 800-53 structure.
- name: PS-6.1 - Information Requiring Special Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ps/ps-6.1.md
  relation: has_enhancement
  description: PS-6 has enhancement PS-6.1.
- name: PS-6.2 - Classified Information Requiring Special Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ps/ps-6.2.md
  relation: has_enhancement
  description: PS-6 has enhancement PS-6.2.
- name: PS-6.3 - Post-employment Requirements
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ps/ps-6.3.md
  relation: has_enhancement
  description: PS-6 has enhancement PS-6.3.
nist_id: PS-6
sort_id: ps-06
implementation_level: organization
parameter_ids:
- ps-06_odp.01
- ps-06_odp.02
reference_links:
- '#ac-17'
- '#pe-2'
- '#pl-4'
- '#ps-2'
- '#ps-3'
- '#ps-6'
- '#ps-7'
- '#ps-8'
- '#sa-21'
- '#si-12'
---

# Summary

SP 800-53 control PS-6.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Access agreements include nondisclosure agreements, acceptable use agreements, rules of behavior, and conflict-of-interest agreements. Signed access agreements include an acknowledgement that individuals have read, understand, and agree to abide by the constraints associated with organizational systems to which access is authorized. Organizations can use electronic signatures to acknowledge access agreements unless specifically prohibited by organizational policy.

# Parameters

- `ps-06_odp.01`
- `ps-06_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
