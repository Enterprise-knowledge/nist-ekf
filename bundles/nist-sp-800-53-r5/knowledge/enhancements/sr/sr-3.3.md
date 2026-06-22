---
type: control_enhancement
title: SR-3.3 - Sub-tier Flow Down
description: Ensure that the controls included in the contracts of prime contractors are also included in the contracts
  of subcontractors.
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
  description: SR-3.3 - Sub-tier Flow Down is part of its parent SP 800-53 structure.
- name: SR-3 - Supply Chain Controls and Processes
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-3.md
  relation: enhances
  description: SR-3.3 enhances base control SR-3.
nist_id: SR-3.3
sort_id: sr-03.03
implementation_level: organization
parameter_ids: []
reference_links:
- '#sr-3'
- '#sr-5'
- '#sr-8'
---

# Summary

Ensure that the controls included in the contracts of prime contractors are also included in the contracts of subcontractors.

# Statement

Ensure that the controls included in the contracts of prime contractors are also included in the contracts of subcontractors.

# Guidance

To manage supply chain risk effectively and holistically, it is important that organizations ensure that supply chain risk management controls are included at all tiers in the supply chain. This includes ensuring that Tier 1 (prime) contractors have implemented processes to facilitate the "flow down" of supply chain risk management controls to sub-tier contractors. The controls subject to flow down are identified in [SR-3b](#sr-3_smt.b).

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
