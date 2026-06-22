---
type: control_enhancement
title: MP-6.7 - Dual Authorization
description: 'Enforce dual authorization for the sanitization of {{ insert: param, mp-06.07_odp }}.'
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-6.md
  relation: part_of
  description: MP-6.7 - Dual Authorization is part of its parent SP 800-53 structure.
- name: MP-6 - Media Sanitization
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-6.md
  relation: enhances
  description: MP-6.7 enhances base control MP-6.
nist_id: MP-6.7
sort_id: mp-06.07
implementation_level: organization
parameter_ids:
- mp-06.07_odp
reference_links:
- '#mp-6'
- '#ac-3'
- '#mp-2'
---

# Summary

Enforce dual authorization for the sanitization of {{ insert: param, mp-06.07_odp }}.

# Statement

Enforce dual authorization for the sanitization of {{ insert: param, mp-06.07_odp }}.

# Guidance

Organizations employ dual authorization to help ensure that system media sanitization cannot occur unless two technically qualified individuals conduct the designated task. Individuals who sanitize system media possess sufficient skills and expertise to determine if the proposed sanitization reflects applicable federal and organizational standards, policies, and procedures. Dual authorization also helps to ensure that sanitization occurs as intended, protecting against errors and false claims of having performed the sanitization actions. Dual authorization may also be known as two-person control. To reduce the risk of collusion, organizations consider rotating dual authorization duties to other individuals.

# Parameters

- `mp-06.07_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
