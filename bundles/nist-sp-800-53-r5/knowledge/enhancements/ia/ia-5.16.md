---
type: control_enhancement
title: IA-5.16 - In-person or Trusted External Party Authenticator Issuance
description: 'Require that the issuance of {{ insert: param, ia-05.16_odp.01 }} be conducted {{ insert: param, ia-05.16_odp.02
  }} before {{ insert: param, ia-05.16_odp.03 }} with authorization by {{ insert: param, ia-05.16_odp.04 }}.'
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
- ia
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-5.md
  relation: part_of
  description: IA-5.16 - In-person or Trusted External Party Authenticator Issuance is part of its parent SP 800-53
    structure.
- name: IA-5 - Authenticator Management
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-5.md
  relation: enhances
  description: IA-5.16 enhances base control IA-5.
nist_id: IA-5.16
sort_id: ia-05.16
implementation_level: organization
parameter_ids:
- ia-05.16_odp.01
- ia-05.16_odp.02
- ia-05.16_odp.03
- ia-05.16_odp.04
reference_links:
- '#ia-5'
- '#ia-12'
---

# Summary

Require that the issuance of {{ insert: param, ia-05.16_odp.01 }} be conducted {{ insert: param, ia-05.16_odp.02 }} before {{ insert: param, ia-05.16_odp.03 }} with authorization by {{ insert: param, ia-05.16_odp.04 }}.

# Statement

Require that the issuance of {{ insert: param, ia-05.16_odp.01 }} be conducted {{ insert: param, ia-05.16_odp.02 }} before {{ insert: param, ia-05.16_odp.03 }} with authorization by {{ insert: param, ia-05.16_odp.04 }}.

# Guidance

Issuing authenticators in person or by a trusted external party enhances and reinforces the trustworthiness of the identity proofing process.

# Parameters

- `ia-05.16_odp.01`
- `ia-05.16_odp.02`
- `ia-05.16_odp.03`
- `ia-05.16_odp.04`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
