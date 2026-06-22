---
type: control
title: MA-7 - Field Maintenance
description: 'Restrict or prohibit field maintenance on {{ insert: param, ma-07_odp.01 }} to {{ insert: param, ma-07_odp.02
  }}.'
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
- ma
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ma.md
  relation: part_of
  description: MA-7 - Field Maintenance is part of its parent SP 800-53 structure.
nist_id: MA-7
sort_id: ma-07
implementation_level: organization
parameter_ids:
- ma-07_odp.01
- ma-07_odp.02
reference_links:
- '#ma-2'
- '#ma-4'
- '#ma-5'
---

# Summary

Restrict or prohibit field maintenance on {{ insert: param, ma-07_odp.01 }} to {{ insert: param, ma-07_odp.02 }}.

# Statement

Restrict or prohibit field maintenance on {{ insert: param, ma-07_odp.01 }} to {{ insert: param, ma-07_odp.02 }}.

# Guidance

Field maintenance is the type of maintenance conducted on a system or system component after the system or component has been deployed to a specific site (i.e., operational environment). In certain instances, field maintenance (i.e., local maintenance at the site) may not be executed with the same degree of rigor or with the same quality control checks as depot maintenance. For critical systems designated as such by the organization, it may be necessary to restrict or prohibit field maintenance at the local site and require that such maintenance be conducted in trusted facilities with additional controls.

# Parameters

- `ma-07_odp.01`
- `ma-07_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
