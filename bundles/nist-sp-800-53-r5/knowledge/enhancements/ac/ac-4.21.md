---
type: control_enhancement
title: AC-4.21 - Physical or Logical Separation of Information Flows
description: 'Separate information flows logically or physically using {{ insert: param, ac-4.21_prm_1 }} to accomplish
  {{ insert: param, ac-04.21_odp.03 }}.'
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
  description: AC-4.21 - Physical or Logical Separation of Information Flows is part of its parent SP 800-53 structure.
- name: AC-4 - Information Flow Enforcement
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-4.md
  relation: enhances
  description: AC-4.21 enhances base control AC-4.
nist_id: AC-4.21
sort_id: ac-04.21
implementation_level: organization
parameter_ids:
- ac-4.21_prm_1
- ac-04.21_odp.01
- ac-04.21_odp.02
- ac-04.21_odp.03
reference_links:
- '#ac-4'
- '#sc-32'
---

# Summary

Separate information flows logically or physically using {{ insert: param, ac-4.21_prm_1 }} to accomplish {{ insert: param, ac-04.21_odp.03 }}.

# Statement

Separate information flows logically or physically using {{ insert: param, ac-4.21_prm_1 }} to accomplish {{ insert: param, ac-04.21_odp.03 }}.

# Guidance

Enforcing the separation of information flows associated with defined types of data can enhance protection by ensuring that information is not commingled while in transit and by enabling flow control by transmission paths that are not otherwise achievable. Types of separable information include inbound and outbound communications traffic, service requests and responses, and information of differing security impact or classification levels.

# Parameters

- `ac-4.21_prm_1`
- `ac-04.21_odp.01`
- `ac-04.21_odp.02`
- `ac-04.21_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
