---
type: control
title: MA-6 - Timely Maintenance
description: 'Obtain maintenance support and/or spare parts for {{ insert: param, ma-06_odp.01 }} within {{ insert:
  param, ma-06_odp.02 }} of failure.'
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
  description: MA-6 - Timely Maintenance is part of its parent SP 800-53 structure.
- name: MA-6.1 - Preventive Maintenance
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-6.1.md
  relation: has_enhancement
  description: MA-6 has enhancement MA-6.1.
- name: MA-6.2 - Predictive Maintenance
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-6.2.md
  relation: has_enhancement
  description: MA-6 has enhancement MA-6.2.
- name: MA-6.3 - Automated Support for Predictive Maintenance
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-6.3.md
  relation: has_enhancement
  description: MA-6 has enhancement MA-6.3.
nist_id: MA-6
sort_id: ma-06
implementation_level: organization
parameter_ids:
- ma-06_odp.01
- ma-06_odp.02
reference_links:
- '#cm-8'
- '#cp-2'
- '#cp-7'
- '#ra-7'
- '#sa-15'
- '#si-13'
- '#sr-2'
- '#sr-3'
- '#sr-4'
---

# Summary

Obtain maintenance support and/or spare parts for {{ insert: param, ma-06_odp.01 }} within {{ insert: param, ma-06_odp.02 }} of failure.

# Statement

Obtain maintenance support and/or spare parts for {{ insert: param, ma-06_odp.01 }} within {{ insert: param, ma-06_odp.02 }} of failure.

# Guidance

Organizations specify the system components that result in increased risk to organizational operations and assets, individuals, other organizations, or the Nation when the functionality provided by those components is not operational. Organizational actions to obtain maintenance support include having appropriate contracts in place.

# Parameters

- `ma-06_odp.01`
- `ma-06_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
