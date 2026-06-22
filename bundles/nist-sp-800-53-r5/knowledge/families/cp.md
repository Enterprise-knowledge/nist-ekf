---
type: control_family
title: CP - Contingency Planning
description: SP 800-53 control family for Contingency Planning.
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
- cp
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
- name: CP-1 - Policy and Procedures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-1.md
  relation: contains
  description: The family contains control CP-1.
- name: CP-2 - Contingency Plan
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-2.md
  relation: contains
  description: The family contains control CP-2.
- name: CP-3 - Contingency Training
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-3.md
  relation: contains
  description: The family contains control CP-3.
- name: CP-4 - Contingency Plan Testing
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-4.md
  relation: contains
  description: The family contains control CP-4.
- name: CP-5 - Contingency Plan Update
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-5.md
  relation: contains
  description: The family contains control CP-5.
- name: CP-6 - Alternate Storage Site
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-6.md
  relation: contains
  description: The family contains control CP-6.
- name: CP-7 - Alternate Processing Site
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-7.md
  relation: contains
  description: The family contains control CP-7.
- name: CP-8 - Telecommunications Services
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-8.md
  relation: contains
  description: The family contains control CP-8.
- name: CP-9 - System Backup
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-9.md
  relation: contains
  description: The family contains control CP-9.
- name: CP-10 - System Recovery and Reconstitution
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-10.md
  relation: contains
  description: The family contains control CP-10.
- name: CP-11 - Alternate Communications Protocols
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-11.md
  relation: contains
  description: The family contains control CP-11.
- name: CP-12 - Safe Mode
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-12.md
  relation: contains
  description: The family contains control CP-12.
- name: CP-13 - Alternative Security Mechanisms
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-13.md
  relation: contains
  description: The family contains control CP-13.
nist_id: CP
base_control_count: 13
control_enhancement_count: 43
---

# Summary

The Contingency Planning family contains 13 base controls and 43 control enhancements in the NIST OSCAL catalog.

# Controls

- [CP-1 - Policy and Procedures](../controls/cp/cp-1.md) - SP 800-53 control CP-1.
- [CP-2 - Contingency Plan](../controls/cp/cp-2.md) - SP 800-53 control CP-2.
- [CP-3 - Contingency Training](../controls/cp/cp-3.md) - SP 800-53 control CP-3.
- [CP-4 - Contingency Plan Testing](../controls/cp/cp-4.md) - SP 800-53 control CP-4.
- [CP-5 - Contingency Plan Update](../controls/cp/cp-5.md) - SP 800-53 control CP-5.
- [CP-6 - Alternate Storage Site](../controls/cp/cp-6.md) - SP 800-53 control CP-6.
- [CP-7 - Alternate Processing Site](../controls/cp/cp-7.md) - SP 800-53 control CP-7.
- [CP-8 - Telecommunications Services](../controls/cp/cp-8.md) - Establish alternate telecommunications services, including necessary agreements to permit the resumption of {{ insert: param, cp-08_odp.01 }} for essential mission and business functions within {{ insert: param, cp-08_od
- [CP-9 - System Backup](../controls/cp/cp-9.md) - SP 800-53 control CP-9.
- [CP-10 - System Recovery and Reconstitution](../controls/cp/cp-10.md) - Provide for the recovery and reconstitution of the system to a known state within {{ insert: param, cp-10_prm_1 }} after a disruption, compromise, or failure.
- [CP-11 - Alternate Communications Protocols](../controls/cp/cp-11.md) - Provide the capability to employ {{ insert: param, cp-11_odp }} in support of maintaining continuity of operations.
- [CP-12 - Safe Mode](../controls/cp/cp-12.md) - When {{ insert: param, cp-12_odp.02 }} are detected, enter a safe mode of operation with {{ insert: param, cp-12_odp.01 }}.
- [CP-13 - Alternative Security Mechanisms](../controls/cp/cp-13.md) - Employ {{ insert: param, cp-13_odp.01 }} for satisfying {{ insert: param, cp-13_odp.02 }} when the primary means of implementing the security function is unavailable or compromised.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
