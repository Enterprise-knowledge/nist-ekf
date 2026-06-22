---
type: control_enhancement
title: IR-4.8 - Correlation with External Organizations
description: 'Coordinate with {{ insert: param, ir-04.08_odp.01 }} to correlate and share {{ insert: param, ir-04.08_odp.02
  }} to achieve a cross-organization perspective on incident awareness and more effective incident responses.'
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
- ir
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-4.md
  relation: part_of
  description: IR-4.8 - Correlation with External Organizations is part of its parent SP 800-53 structure.
- name: IR-4 - Incident Handling
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-4.md
  relation: enhances
  description: IR-4.8 enhances base control IR-4.
nist_id: IR-4.8
sort_id: ir-04.08
implementation_level: organization
parameter_ids:
- ir-04.08_odp.01
- ir-04.08_odp.02
reference_links:
- '#ir-4'
- '#au-16'
- '#pm-16'
---

# Summary

Coordinate with {{ insert: param, ir-04.08_odp.01 }} to correlate and share {{ insert: param, ir-04.08_odp.02 }} to achieve a cross-organization perspective on incident awareness and more effective incident responses.

# Statement

Coordinate with {{ insert: param, ir-04.08_odp.01 }} to correlate and share {{ insert: param, ir-04.08_odp.02 }} to achieve a cross-organization perspective on incident awareness and more effective incident responses.

# Guidance

The coordination of incident information with external organizations—including mission or business partners, military or coalition partners, customers, and developers—can provide significant benefits. Cross-organizational coordination can serve as an important risk management capability. This capability allows organizations to leverage information from a variety of sources to effectively respond to incidents and breaches that could potentially affect the organization’s operations, assets, and individuals.

# Parameters

- `ir-04.08_odp.01`
- `ir-04.08_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
