---
type: control_enhancement
title: SC-5.2 - Capacity, Bandwidth, and Redundancy
description: Manage capacity, bandwidth, or other redundancy to limit the effects of information flooding denial-of-service
  attacks.
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
- sc
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-5.md
  relation: part_of
  description: SC-5.2 - Capacity, Bandwidth, and Redundancy is part of its parent SP 800-53 structure.
- name: SC-5 - Denial-of-service Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-5.md
  relation: enhances
  description: SC-5.2 enhances base control SC-5.
nist_id: SC-5.2
sort_id: sc-05.02
implementation_level: system
parameter_ids: []
reference_links:
- '#sc-5'
---

# Summary

Manage capacity, bandwidth, or other redundancy to limit the effects of information flooding denial-of-service attacks.

# Statement

Manage capacity, bandwidth, or other redundancy to limit the effects of information flooding denial-of-service attacks.

# Guidance

Managing capacity ensures that sufficient capacity is available to counter flooding attacks. Managing capacity includes establishing selected usage priorities, quotas, partitioning, or load balancing.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
