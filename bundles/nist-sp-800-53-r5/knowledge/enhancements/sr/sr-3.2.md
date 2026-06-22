---
type: control_enhancement
title: SR-3.2 - Limitation of Harm
description: 'Employ the following controls to limit harm from potential adversaries identifying and targeting the
  organizational supply chain: {{ insert: param, sr-03.02_odp }}.'
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
- sr
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-3.md
  relation: part_of
  description: SR-3.2 - Limitation of Harm is part of its parent SP 800-53 structure.
- name: SR-3 - Supply Chain Controls and Processes
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-3.md
  relation: enhances
  description: SR-3.2 enhances base control SR-3.
nist_id: SR-3.2
sort_id: sr-03.02
implementation_level: organization
parameter_ids:
- sr-03.02_odp
reference_links:
- '#sr-3'
---

# Summary

Employ the following controls to limit harm from potential adversaries identifying and targeting the organizational supply chain: {{ insert: param, sr-03.02_odp }}.

# Statement

Employ the following controls to limit harm from potential adversaries identifying and targeting the organizational supply chain: {{ insert: param, sr-03.02_odp }}.

# Guidance

Controls that can be implemented to reduce the probability of adversaries successfully identifying and targeting the supply chain include avoiding the purchase of custom or non-standardized configurations, employing approved vendor lists with standing reputations in industry, following pre-agreed maintenance schedules and update and patch delivery mechanisms, maintaining a contingency plan in case of a supply chain event, using procurement carve-outs that provide exclusions to commitments or obligations, using diverse delivery routes, and minimizing the time between purchase decisions and delivery.

# Parameters

- `sr-03.02_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
