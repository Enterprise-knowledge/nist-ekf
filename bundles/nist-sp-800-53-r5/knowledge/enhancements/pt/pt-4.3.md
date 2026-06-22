---
type: control_enhancement
title: PT-4.3 - Revocation
description: 'Implement {{ insert: param, pt-04.03_odp }} for individuals to revoke consent to the processing of
  their personally identifiable information.'
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
- pt
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-4.md
  relation: part_of
  description: PT-4.3 - Revocation is part of its parent SP 800-53 structure.
- name: PT-4 - Consent
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-4.md
  relation: enhances
  description: PT-4.3 enhances base control PT-4.
nist_id: PT-4.3
sort_id: pt-04.03
implementation_level: organization
parameter_ids:
- pt-04.03_odp
reference_links:
- '#pt-4'
- '#pt-2'
---

# Summary

Implement {{ insert: param, pt-04.03_odp }} for individuals to revoke consent to the processing of their personally identifiable information.

# Statement

Implement {{ insert: param, pt-04.03_odp }} for individuals to revoke consent to the processing of their personally identifiable information.

# Guidance

Revocation of consent enables individuals to exercise control over their initial consent decision when circumstances change. Organizations consider usability factors in enabling easy-to-use revocation capabilities.

# Parameters

- `pt-04.03_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
