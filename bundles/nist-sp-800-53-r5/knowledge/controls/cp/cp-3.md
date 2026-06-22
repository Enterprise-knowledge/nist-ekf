---
type: control
title: CP-3 - Contingency Training
description: SP 800-53 control CP-3.
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
  description: CP-3 - Contingency Training is part of its parent SP 800-53 structure.
- name: CP-3.1 - Simulated Events
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-3.1.md
  relation: has_enhancement
  description: CP-3 has enhancement CP-3.1.
- name: CP-3.2 - Mechanisms Used in Training Environments
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-3.2.md
  relation: has_enhancement
  description: CP-3 has enhancement CP-3.2.
nist_id: CP-3
sort_id: cp-03
implementation_level: organization
parameter_ids:
- cp-03_odp.01
- cp-03_odp.02
- cp-03_odp.03
- cp-03_odp.04
reference_links:
- '#511f6832-23ca-49a3-8c0f-ce493373cab8'
- '#at-2'
- '#at-3'
- '#at-4'
- '#cp-2'
- '#cp-4'
- '#cp-8'
- '#ir-2'
- '#ir-4'
- '#ir-9'
---

# Summary

SP 800-53 control CP-3.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Contingency training provided by organizations is linked to the assigned roles and responsibilities of organizational personnel to ensure that the appropriate content and level of detail is included in such training. For example, some individuals may only need to know when and where to report for duty during contingency operations and if normal duties are affected; system administrators may require additional training on how to establish systems at alternate processing and storage sites; and organizational officials may receive more specific training on how to conduct mission-essential functions in designated off-site locations and how to establish communications with other governmental entities for purposes of coordination on contingency-related activities. Training for contingency roles or responsibilities reflects the specific continuity requirements in the contingency plan. Events that may precipitate an update to contingency training content include, but are not limited to, contingency plan testing or an actual contingency (lessons learned), assessment or audit findings, security incidents or breaches, or changes in laws, executive orders, directives, regulations, policies, standards, and guidelines. At the discretion of the organization, participation in a contingency plan test or exercise, including lessons learned sessions subsequent to the test or exercise, may satisfy contingency plan training requirements.

# Parameters

- `cp-03_odp.01`
- `cp-03_odp.02`
- `cp-03_odp.03`
- `cp-03_odp.04`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
