---
type: control
title: PE-8 - Visitor Access Records
description: SP 800-53 control PE-8.
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
  description: PE-8 - Visitor Access Records is part of its parent SP 800-53 structure.
- name: PE-8.1 - Automated Records Maintenance and Review
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-8.1.md
  relation: has_enhancement
  description: PE-8 has enhancement PE-8.1.
- name: PE-8.2 - Physical Access Records
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-8.2.md
  relation: has_enhancement
  description: PE-8 has enhancement PE-8.2.
- name: PE-8.3 - Limit Personally Identifiable Information Elements
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-8.3.md
  relation: has_enhancement
  description: PE-8 has enhancement PE-8.3.
nist_id: PE-8
sort_id: pe-08
implementation_level: organization
parameter_ids:
- pe-08_odp.01
- pe-08_odp.02
- pe-08_odp.03
reference_links:
- '#pe-2'
- '#pe-3'
- '#pe-6'
---

# Summary

SP 800-53 control PE-8.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Visitor access records include the names and organizations of individuals visiting, visitor signatures, forms of identification, dates of access, entry and departure times, purpose of visits, and the names and organizations of individuals visited. Access record reviews determine if access authorizations are current and are still required to support organizational mission and business functions. Access records are not required for publicly accessible areas.

# Parameters

- `pe-08_odp.01`
- `pe-08_odp.02`
- `pe-08_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
