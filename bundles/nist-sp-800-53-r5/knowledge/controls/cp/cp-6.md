---
type: control
title: CP-6 - Alternate Storage Site
description: SP 800-53 control CP-6.
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
  description: CP-6 - Alternate Storage Site is part of its parent SP 800-53 structure.
- name: CP-6.1 - Separation from Primary Site
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-6.1.md
  relation: has_enhancement
  description: CP-6 has enhancement CP-6.1.
- name: CP-6.2 - Recovery Time and Recovery Point Objectives
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-6.2.md
  relation: has_enhancement
  description: CP-6 has enhancement CP-6.2.
- name: CP-6.3 - Accessibility
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-6.3.md
  relation: has_enhancement
  description: CP-6 has enhancement CP-6.3.
nist_id: CP-6
sort_id: cp-06
implementation_level: organization
parameter_ids: []
reference_links:
- '#bc39f179-c735-4da2-b7a7-b2b622119755'
- '#cp-2'
- '#cp-7'
- '#cp-8'
- '#cp-9'
- '#cp-10'
- '#mp-4'
- '#mp-5'
- '#pe-3'
- '#sc-36'
- '#si-13'
---

# Summary

SP 800-53 control CP-6.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Alternate storage sites are geographically distinct from primary storage sites and maintain duplicate copies of information and data if the primary storage site is not available. Similarly, alternate processing sites provide processing capability if the primary processing site is not available. Geographically distributed architectures that support contingency requirements may be considered alternate storage sites. Items covered by alternate storage site agreements include environmental conditions at the alternate sites, access rules for systems and facilities, physical and environmental protection requirements, and coordination of delivery and retrieval of backup media. Alternate storage sites reflect the requirements in contingency plans so that organizations can maintain essential mission and business functions despite compromise, failure, or disruption in organizational systems.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
