---
type: control_enhancement
title: RA-3.3 - Dynamic Threat Awareness
description: 'Determine the current cyber threat environment on an ongoing basis using {{ insert: param, ra-03.03_odp
  }}.'
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
- ra
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-3.md
  relation: part_of
  description: RA-3.3 - Dynamic Threat Awareness is part of its parent SP 800-53 structure.
- name: RA-3 - Risk Assessment
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-3.md
  relation: enhances
  description: RA-3.3 enhances base control RA-3.
nist_id: RA-3.3
sort_id: ra-03.03
implementation_level: organization
parameter_ids:
- ra-03.03_odp
reference_links:
- '#ra-3'
- '#at-2'
---

# Summary

Determine the current cyber threat environment on an ongoing basis using {{ insert: param, ra-03.03_odp }}.

# Statement

Determine the current cyber threat environment on an ongoing basis using {{ insert: param, ra-03.03_odp }}.

# Guidance

The threat awareness information that is gathered feeds into the organization’s information security operations to ensure that procedures are updated in response to the changing threat environment. For example, at higher threat levels, organizations may change the privilege or authentication thresholds required to perform certain operations.

# Parameters

- `ra-03.03_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
