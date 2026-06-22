---
type: control
title: AU-4 - Audit Log Storage Capacity
description: 'Allocate audit log storage capacity to accommodate {{ insert: param, au-04_odp }}.'
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
- au
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/au.md
  relation: part_of
  description: AU-4 - Audit Log Storage Capacity is part of its parent SP 800-53 structure.
- name: AU-4.1 - Transfer to Alternate Storage
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-4.1.md
  relation: has_enhancement
  description: AU-4 has enhancement AU-4.1.
nist_id: AU-4
sort_id: au-04
implementation_level: organization
parameter_ids:
- au-04_odp
reference_links:
- '#au-2'
- '#au-5'
- '#au-6'
- '#au-7'
- '#au-9'
- '#au-11'
- '#au-12'
- '#au-14'
- '#si-4'
---

# Summary

Allocate audit log storage capacity to accommodate {{ insert: param, au-04_odp }}.

# Statement

Allocate audit log storage capacity to accommodate {{ insert: param, au-04_odp }}.

# Guidance

Organizations consider the types of audit logging to be performed and the audit log processing requirements when allocating audit log storage capacity. Allocating sufficient audit log storage capacity reduces the likelihood of such capacity being exceeded and resulting in the potential loss or reduction of audit logging capability.

# Parameters

- `au-04_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
