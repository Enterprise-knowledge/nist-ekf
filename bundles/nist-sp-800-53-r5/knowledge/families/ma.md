---
type: control_family
title: MA - Maintenance
description: SP 800-53 control family for Maintenance.
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control-family
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
- name: The Controls
  path: /bundles/nist-sp-800-53-r5/knowledge/sections/controls.md
  relation: part_of
  description: This family is part of the controls section.
- name: MA-1 - Policy and Procedures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-1.md
  relation: contains
  description: The family contains control MA-1.
- name: MA-2 - Controlled Maintenance
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-2.md
  relation: contains
  description: The family contains control MA-2.
- name: MA-3 - Maintenance Tools
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-3.md
  relation: contains
  description: The family contains control MA-3.
- name: MA-4 - Nonlocal Maintenance
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-4.md
  relation: contains
  description: The family contains control MA-4.
- name: MA-5 - Maintenance Personnel
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-5.md
  relation: contains
  description: The family contains control MA-5.
- name: MA-6 - Timely Maintenance
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-6.md
  relation: contains
  description: The family contains control MA-6.
- name: MA-7 - Field Maintenance
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-7.md
  relation: contains
  description: The family contains control MA-7.
nist_id: MA
base_control_count: 7
control_enhancement_count: 23
---

# Summary

The Maintenance family contains 7 base controls and 23 control enhancements in the NIST OSCAL catalog.

# Controls

- [MA-1 - Policy and Procedures](../controls/ma/ma-1.md) - SP 800-53 control MA-1.
- [MA-2 - Controlled Maintenance](../controls/ma/ma-2.md) - SP 800-53 control MA-2.
- [MA-3 - Maintenance Tools](../controls/ma/ma-3.md) - SP 800-53 control MA-3.
- [MA-4 - Nonlocal Maintenance](../controls/ma/ma-4.md) - SP 800-53 control MA-4.
- [MA-5 - Maintenance Personnel](../controls/ma/ma-5.md) - SP 800-53 control MA-5.
- [MA-6 - Timely Maintenance](../controls/ma/ma-6.md) - Obtain maintenance support and/or spare parts for {{ insert: param, ma-06_odp.01 }} within {{ insert: param, ma-06_odp.02 }} of failure.
- [MA-7 - Field Maintenance](../controls/ma/ma-7.md) - Restrict or prohibit field maintenance on {{ insert: param, ma-07_odp.01 }} to {{ insert: param, ma-07_odp.02 }}.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
