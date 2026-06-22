---
type: control_enhancement
title: AC-4.15 - Detection of Unsanctioned Information
description: 'When transferring information between different security domains, examine the information for the
  presence of {{ insert: param, ac-04.15_odp.01 }} and prohibit the transfer of such information in accordance with
  the {{ i'
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
  description: AC-4.15 - Detection of Unsanctioned Information is part of its parent SP 800-53 structure.
- name: AC-4 - Information Flow Enforcement
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-4.md
  relation: enhances
  description: AC-4.15 enhances base control AC-4.
nist_id: AC-4.15
sort_id: ac-04.15
implementation_level: system
parameter_ids:
- ac-4.15_prm_2
- ac-04.15_odp.01
- ac-04.15_odp.02
- ac-04.15_odp.03
reference_links:
- '#ac-4'
- '#si-3'
---

# Summary

When transferring information between different security domains, examine the information for the presence of {{ insert: param, ac-04.15_odp.01 }} and prohibit the transfer of such information in accordance with the {{ i

# Statement

When transferring information between different security domains, examine the information for the presence of {{ insert: param, ac-04.15_odp.01 }} and prohibit the transfer of such information in accordance with the {{ insert: param, ac-4.15_prm_2 }}.

# Guidance

Unsanctioned information includes malicious code, information that is inappropriate for release from the source network, or executable code that could disrupt or harm the services or systems on the destination network.

# Parameters

- `ac-4.15_prm_2`
- `ac-04.15_odp.01`
- `ac-04.15_odp.02`
- `ac-04.15_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
