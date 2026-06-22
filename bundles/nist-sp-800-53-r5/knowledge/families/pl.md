---
type: control_family
title: PL - Planning
description: SP 800-53 control family for Planning.
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
- pl
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
- name: PL-1 - Policy and Procedures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pl/pl-1.md
  relation: contains
  description: The family contains control PL-1.
- name: PL-2 - System Security and Privacy Plans
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pl/pl-2.md
  relation: contains
  description: The family contains control PL-2.
- name: PL-3 - System Security Plan Update
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pl/pl-3.md
  relation: contains
  description: The family contains control PL-3.
- name: PL-4 - Rules of Behavior
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pl/pl-4.md
  relation: contains
  description: The family contains control PL-4.
- name: PL-5 - Privacy Impact Assessment
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pl/pl-5.md
  relation: contains
  description: The family contains control PL-5.
- name: PL-6 - Security-related Activity Planning
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pl/pl-6.md
  relation: contains
  description: The family contains control PL-6.
- name: PL-7 - Concept of Operations
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pl/pl-7.md
  relation: contains
  description: The family contains control PL-7.
- name: PL-8 - Security and Privacy Architectures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pl/pl-8.md
  relation: contains
  description: The family contains control PL-8.
- name: PL-9 - Central Management
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pl/pl-9.md
  relation: contains
  description: The family contains control PL-9.
- name: PL-10 - Baseline Selection
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pl/pl-10.md
  relation: contains
  description: The family contains control PL-10.
- name: PL-11 - Baseline Tailoring
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pl/pl-11.md
  relation: contains
  description: The family contains control PL-11.
nist_id: PL
base_control_count: 11
control_enhancement_count: 6
---

# Summary

The Planning family contains 11 base controls and 6 control enhancements in the NIST OSCAL catalog.

# Controls

- [PL-1 - Policy and Procedures](../controls/pl/pl-1.md) - SP 800-53 control PL-1.
- [PL-2 - System Security and Privacy Plans](../controls/pl/pl-2.md) - SP 800-53 control PL-2.
- [PL-3 - System Security Plan Update](../controls/pl/pl-3.md) - SP 800-53 control PL-3.
- [PL-4 - Rules of Behavior](../controls/pl/pl-4.md) - SP 800-53 control PL-4.
- [PL-5 - Privacy Impact Assessment](../controls/pl/pl-5.md) - SP 800-53 control PL-5.
- [PL-6 - Security-related Activity Planning](../controls/pl/pl-6.md) - SP 800-53 control PL-6.
- [PL-7 - Concept of Operations](../controls/pl/pl-7.md) - SP 800-53 control PL-7.
- [PL-8 - Security and Privacy Architectures](../controls/pl/pl-8.md) - SP 800-53 control PL-8.
- [PL-9 - Central Management](../controls/pl/pl-9.md) - Centrally manage {{ insert: param, pl-09_odp }}.
- [PL-10 - Baseline Selection](../controls/pl/pl-10.md) - Select a control baseline for the system.
- [PL-11 - Baseline Tailoring](../controls/pl/pl-11.md) - Tailor the selected control baseline by applying specified tailoring actions.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
