---
type: control_enhancement
title: CP-2.8 - Identify Critical Assets
description: 'Identify critical system assets supporting {{ insert: param, cp-02.08_odp }} mission and business
  functions.'
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-2.md
  relation: part_of
  description: CP-2.8 - Identify Critical Assets is part of its parent SP 800-53 structure.
- name: CP-2 - Contingency Plan
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-2.md
  relation: enhances
  description: CP-2.8 enhances base control CP-2.
nist_id: CP-2.8
sort_id: cp-02.08
implementation_level: organization
parameter_ids:
- cp-02.08_odp
reference_links:
- '#cp-2'
- '#cm-8'
- '#ra-9'
---

# Summary

Identify critical system assets supporting {{ insert: param, cp-02.08_odp }} mission and business functions.

# Statement

Identify critical system assets supporting {{ insert: param, cp-02.08_odp }} mission and business functions.

# Guidance

Organizations may choose to identify critical assets as part of criticality analysis, business continuity planning, or business impact analyses. Organizations identify critical system assets so that additional controls can be employed (beyond the controls routinely implemented) to help ensure that organizational mission and business functions can continue to be conducted during contingency operations. The identification of critical information assets also facilitates the prioritization of organizational resources. Critical system assets include technical and operational aspects. Technical aspects include system components, information technology services, information technology products, and mechanisms. Operational aspects include procedures (i.e., manually executed operations) and personnel (i.e., individuals operating technical controls and/or executing manual procedures). Organizational program protection plans can assist in identifying critical assets. If critical assets are resident within or supported by external service providers, organizations consider implementing [CP-2(7)](#cp-2.7) as a control enhancement.

# Parameters

- `cp-02.08_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
