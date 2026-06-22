---
type: control
title: CP-8 - Telecommunications Services
description: 'Establish alternate telecommunications services, including necessary agreements to permit the resumption
  of {{ insert: param, cp-08_odp.01 }} for essential mission and business functions within {{ insert: param, cp-08_od'
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control
- cp
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/cp.md
  relation: part_of
  description: CP-8 - Telecommunications Services is part of its parent SP 800-53 structure.
- name: CP-8.1 - Priority of Service Provisions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-8.1.md
  relation: has_enhancement
  description: CP-8 has enhancement CP-8.1.
- name: CP-8.2 - Single Points of Failure
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-8.2.md
  relation: has_enhancement
  description: CP-8 has enhancement CP-8.2.
- name: CP-8.3 - Separation of Primary and Alternate Providers
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-8.3.md
  relation: has_enhancement
  description: CP-8 has enhancement CP-8.3.
- name: CP-8.4 - Provider Contingency Plan
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-8.4.md
  relation: has_enhancement
  description: CP-8 has enhancement CP-8.4.
- name: CP-8.5 - Alternate Telecommunication Service Testing
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-8.5.md
  relation: has_enhancement
  description: CP-8 has enhancement CP-8.5.
nist_id: CP-8
sort_id: cp-08
implementation_level: organization
parameter_ids:
- cp-08_odp.01
- cp-08_odp.02
reference_links:
- '#bc39f179-c735-4da2-b7a7-b2b622119755'
- '#cp-2'
- '#cp-6'
- '#cp-7'
- '#cp-11'
- '#sc-7'
---

# Summary

Establish alternate telecommunications services, including necessary agreements to permit the resumption of {{ insert: param, cp-08_odp.01 }} for essential mission and business functions within {{ insert: param, cp-08_od

# Statement

Establish alternate telecommunications services, including necessary agreements to permit the resumption of {{ insert: param, cp-08_odp.01 }} for essential mission and business functions within {{ insert: param, cp-08_odp.02 }} when the primary telecommunications capabilities are unavailable at either the primary or alternate processing or storage sites.

# Guidance

Telecommunications services (for data and voice) for primary and alternate processing and storage sites are in scope for [CP-8](#cp-8) . Alternate telecommunications services reflect the continuity requirements in contingency plans to maintain essential mission and business functions despite the loss of primary telecommunications services. Organizations may specify different time periods for primary or alternate sites. Alternate telecommunications services include additional organizational or commercial ground-based circuits or lines, network-based approaches to telecommunications, or the use of satellites. Organizations consider factors such as availability, quality of service, and access when entering into alternate telecommunications agreements.

# Parameters

- `cp-08_odp.01`
- `cp-08_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
