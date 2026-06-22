---
type: control_enhancement
title: SR-3.1 - Diverse Supply Base
description: 'Employ a diverse set of sources for the following system components and services: {{ insert: param,
  sr-3.1_prm_1 }}.'
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
  description: SR-3.1 - Diverse Supply Base is part of its parent SP 800-53 structure.
- name: SR-3 - Supply Chain Controls and Processes
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-3.md
  relation: enhances
  description: SR-3.1 enhances base control SR-3.
nist_id: SR-3.1
sort_id: sr-03.01
implementation_level: organization
parameter_ids:
- sr-3.1_prm_1
- sr-03.01_odp.01
- sr-03.01_odp.02
reference_links:
- '#sr-3'
---

# Summary

Employ a diverse set of sources for the following system components and services: {{ insert: param, sr-3.1_prm_1 }}.

# Statement

Employ a diverse set of sources for the following system components and services: {{ insert: param, sr-3.1_prm_1 }}.

# Guidance

Diversifying the supply of systems, system components, and services can reduce the probability that adversaries will successfully identify and target the supply chain and can reduce the impact of a supply chain event or compromise. Identifying multiple suppliers for replacement components can reduce the probability that the replacement component will become unavailable. Employing a diverse set of developers or logistics service providers can reduce the impact of a natural disaster or other supply chain event. Organizations consider designing the system to include diverse materials and components.

# Parameters

- `sr-3.1_prm_1`
- `sr-03.01_odp.01`
- `sr-03.01_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
