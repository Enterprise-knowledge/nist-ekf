---
type: control_enhancement
title: CM-8.2 - Automated Maintenance
description: 'Maintain the currency, completeness, accuracy, and availability of the inventory of system components
  using {{ insert: param, cm-8.2_prm_1 }}.'
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
- cm
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-8.md
  relation: part_of
  description: CM-8.2 - Automated Maintenance is part of its parent SP 800-53 structure.
- name: CM-8 - System Component Inventory
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-8.md
  relation: enhances
  description: CM-8.2 enhances base control CM-8.
nist_id: CM-8.2
sort_id: cm-08.02
implementation_level: organization
parameter_ids:
- cm-8.2_prm_1
- cm-08.02_odp.01
- cm-08.02_odp.02
- cm-08.02_odp.03
- cm-08.02_odp.04
reference_links:
- '#cm-8'
---

# Summary

Maintain the currency, completeness, accuracy, and availability of the inventory of system components using {{ insert: param, cm-8.2_prm_1 }}.

# Statement

Maintain the currency, completeness, accuracy, and availability of the inventory of system components using {{ insert: param, cm-8.2_prm_1 }}.

# Guidance

Organizations maintain system inventories to the extent feasible. For example, virtual machines can be difficult to monitor because such machines are not visible to the network when not in use. In such cases, organizations maintain as up-to-date, complete, and accurate an inventory as is deemed reasonable. Automated maintenance can be achieved by the implementation of [CM-2(2)](#cm-2.2) for organizations that combine system component inventory and baseline configuration activities.

# Parameters

- `cm-8.2_prm_1`
- `cm-08.02_odp.01`
- `cm-08.02_odp.02`
- `cm-08.02_odp.03`
- `cm-08.02_odp.04`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
