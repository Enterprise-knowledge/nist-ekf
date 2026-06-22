---
type: control_enhancement
title: IA-5.13 - Expiration of Cached Authenticators
description: 'Prohibit the use of cached authenticators after {{ insert: param, ia-05.13_odp }}.'
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
  description: IA-5.13 - Expiration of Cached Authenticators is part of its parent SP 800-53 structure.
- name: IA-5 - Authenticator Management
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-5.md
  relation: enhances
  description: IA-5.13 enhances base control IA-5.
nist_id: IA-5.13
sort_id: ia-05.13
implementation_level: system
parameter_ids:
- ia-05.13_odp
reference_links:
- '#ia-5'
---

# Summary

Prohibit the use of cached authenticators after {{ insert: param, ia-05.13_odp }}.

# Statement

Prohibit the use of cached authenticators after {{ insert: param, ia-05.13_odp }}.

# Guidance

Cached authenticators are used to authenticate to the local machine when the network is not available. If cached authentication information is out of date, the validity of the authentication information may be questionable.

# Parameters

- `ia-05.13_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
