---
type: control_family
title: MP - Media Protection
description: SP 800-53 control family for Media Protection.
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
- mp
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
- name: MP-1 - Policy and Procedures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-1.md
  relation: contains
  description: The family contains control MP-1.
- name: MP-2 - Media Access
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-2.md
  relation: contains
  description: The family contains control MP-2.
- name: MP-3 - Media Marking
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-3.md
  relation: contains
  description: The family contains control MP-3.
- name: MP-4 - Media Storage
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-4.md
  relation: contains
  description: The family contains control MP-4.
- name: MP-5 - Media Transport
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-5.md
  relation: contains
  description: The family contains control MP-5.
- name: MP-6 - Media Sanitization
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-6.md
  relation: contains
  description: The family contains control MP-6.
- name: MP-7 - Media Use
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-7.md
  relation: contains
  description: The family contains control MP-7.
- name: MP-8 - Media Downgrading
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-8.md
  relation: contains
  description: The family contains control MP-8.
nist_id: MP
base_control_count: 8
control_enhancement_count: 22
---

# Summary

The Media Protection family contains 8 base controls and 22 control enhancements in the NIST OSCAL catalog.

# Controls

- [MP-1 - Policy and Procedures](../controls/mp/mp-1.md) - SP 800-53 control MP-1.
- [MP-2 - Media Access](../controls/mp/mp-2.md) - Restrict access to {{ insert: param, mp-2_prm_1 }} to {{ insert: param, mp-2_prm_2 }}.
- [MP-3 - Media Marking](../controls/mp/mp-3.md) - SP 800-53 control MP-3.
- [MP-4 - Media Storage](../controls/mp/mp-4.md) - SP 800-53 control MP-4.
- [MP-5 - Media Transport](../controls/mp/mp-5.md) - SP 800-53 control MP-5.
- [MP-6 - Media Sanitization](../controls/mp/mp-6.md) - SP 800-53 control MP-6.
- [MP-7 - Media Use](../controls/mp/mp-7.md) - SP 800-53 control MP-7.
- [MP-8 - Media Downgrading](../controls/mp/mp-8.md) - SP 800-53 control MP-8.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
