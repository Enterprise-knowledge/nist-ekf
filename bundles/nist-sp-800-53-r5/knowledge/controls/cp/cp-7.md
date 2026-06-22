---
type: control
title: CP-7 - Alternate Processing Site
description: SP 800-53 control CP-7.
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
  description: CP-7 - Alternate Processing Site is part of its parent SP 800-53 structure.
- name: CP-7.1 - Separation from Primary Site
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-7.1.md
  relation: has_enhancement
  description: CP-7 has enhancement CP-7.1.
- name: CP-7.2 - Accessibility
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-7.2.md
  relation: has_enhancement
  description: CP-7 has enhancement CP-7.2.
- name: CP-7.3 - Priority of Service
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-7.3.md
  relation: has_enhancement
  description: CP-7 has enhancement CP-7.3.
- name: CP-7.4 - Preparation for Use
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-7.4.md
  relation: has_enhancement
  description: CP-7 has enhancement CP-7.4.
- name: CP-7.5 - Equivalent Information Security Safeguards
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-7.5.md
  relation: has_enhancement
  description: CP-7 has enhancement CP-7.5.
- name: CP-7.6 - Inability to Return to Primary Site
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-7.6.md
  relation: has_enhancement
  description: CP-7 has enhancement CP-7.6.
nist_id: CP-7
sort_id: cp-07
implementation_level: organization
parameter_ids:
- cp-07_odp.01
- cp-07_odp.02
reference_links:
- '#bc39f179-c735-4da2-b7a7-b2b622119755'
- '#cp-2'
- '#cp-6'
- '#cp-8'
- '#cp-9'
- '#cp-10'
- '#ma-6'
- '#pe-3'
- '#pe-11'
- '#pe-12'
- '#pe-17'
- '#sc-36'
- '#si-13'
---

# Summary

SP 800-53 control CP-7.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Alternate processing sites are geographically distinct from primary processing sites and provide processing capability if the primary processing site is not available. The alternate processing capability may be addressed using a physical processing site or other alternatives, such as failover to a cloud-based service provider or other internally or externally provided processing service. Geographically distributed architectures that support contingency requirements may also be considered alternate processing sites. Controls that are covered by alternate processing site agreements include the environmental conditions at alternate sites, access rules, physical and environmental protection requirements, and the coordination for the transfer and assignment of personnel. Requirements are allocated to alternate processing sites that reflect the requirements in contingency plans to maintain essential mission and business functions despite disruption, compromise, or failure in organizational systems.

# Parameters

- `cp-07_odp.01`
- `cp-07_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
