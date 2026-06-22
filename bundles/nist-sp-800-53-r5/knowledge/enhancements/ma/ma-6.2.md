---
type: control_enhancement
title: MA-6.2 - Predictive Maintenance
description: 'Perform predictive maintenance on {{ insert: param, ma-06.02_odp.01 }} at {{ insert: param, ma-06.02_odp.02
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
- control-enhancement
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-6.md
  relation: part_of
  description: MA-6.2 - Predictive Maintenance is part of its parent SP 800-53 structure.
- name: MA-6 - Timely Maintenance
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-6.md
  relation: enhances
  description: MA-6.2 enhances base control MA-6.
nist_id: MA-6.2
sort_id: ma-06.02
implementation_level: organization
parameter_ids:
- ma-06.02_odp.01
- ma-06.02_odp.02
reference_links:
- '#ma-6'
---

# Summary

Perform predictive maintenance on {{ insert: param, ma-06.02_odp.01 }} at {{ insert: param, ma-06.02_odp.02 }}.

# Statement

Perform predictive maintenance on {{ insert: param, ma-06.02_odp.01 }} at {{ insert: param, ma-06.02_odp.02 }}.

# Guidance

Predictive maintenance evaluates the condition of equipment by performing periodic or continuous (online) equipment condition monitoring. The goal of predictive maintenance is to perform maintenance at a scheduled time when the maintenance activity is most cost-effective and before the equipment loses performance within a threshold. The predictive component of predictive maintenance stems from the objective of predicting the future trend of the equipment's condition. The predictive maintenance approach employs principles of statistical process control to determine at what point in the future maintenance activities will be appropriate. Most predictive maintenance inspections are performed while equipment is in service, thus minimizing disruption of normal system operations. Predictive maintenance can result in substantial cost savings and higher system reliability.

# Parameters

- `ma-06.02_odp.01`
- `ma-06.02_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
