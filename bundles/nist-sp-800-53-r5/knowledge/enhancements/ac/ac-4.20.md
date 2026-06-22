---
type: control_enhancement
title: AC-4.20 - Approved Solutions
description: 'Employ {{ insert: param, ac-04.20_odp.01 }} to control the flow of {{ insert: param, ac-04.20_odp.02
  }} across security domains.'
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
- ac
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-4.md
  relation: part_of
  description: AC-4.20 - Approved Solutions is part of its parent SP 800-53 structure.
- name: AC-4 - Information Flow Enforcement
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-4.md
  relation: enhances
  description: AC-4.20 enhances base control AC-4.
nist_id: AC-4.20
sort_id: ac-04.20
implementation_level: organization
parameter_ids:
- ac-04.20_odp.01
- ac-04.20_odp.02
reference_links:
- '#ac-4'
---

# Summary

Employ {{ insert: param, ac-04.20_odp.01 }} to control the flow of {{ insert: param, ac-04.20_odp.02 }} across security domains.

# Statement

Employ {{ insert: param, ac-04.20_odp.01 }} to control the flow of {{ insert: param, ac-04.20_odp.02 }} across security domains.

# Guidance

Organizations define approved solutions and configurations in cross-domain policies and guidance in accordance with the types of information flows across classification boundaries. The National Security Agency (NSA) National Cross Domain Strategy and Management Office provides a listing of approved cross-domain solutions. Contact [ncdsmo@nsa.gov](mailto:ncdsmo@nsa.gov) for more information.

# Parameters

- `ac-04.20_odp.01`
- `ac-04.20_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
