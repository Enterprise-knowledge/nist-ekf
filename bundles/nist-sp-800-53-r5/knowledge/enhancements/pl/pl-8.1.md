---
type: control_enhancement
title: PL-8.1 - Defense in Depth
description: 'Design the security and privacy architectures for the system using a defense-in-depth approach that:'
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
- pl
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pl/pl-8.md
  relation: part_of
  description: PL-8.1 - Defense in Depth is part of its parent SP 800-53 structure.
- name: PL-8 - Security and Privacy Architectures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pl/pl-8.md
  relation: enhances
  description: PL-8.1 enhances base control PL-8.
nist_id: PL-8.1
sort_id: pl-08.01
implementation_level: organization
parameter_ids:
- pl-08.01_odp.01
- pl-08.01_odp.02
reference_links:
- '#pl-8'
- '#sc-2'
- '#sc-3'
- '#sc-29'
- '#sc-36'
---

# Summary

Design the security and privacy architectures for the system using a defense-in-depth approach that:

# Statement

Design the security and privacy architectures for the system using a defense-in-depth approach that:

# Guidance

Organizations strategically allocate security and privacy controls in the security and privacy architectures so that adversaries must overcome multiple controls to achieve their objective. Requiring adversaries to defeat multiple controls makes it more difficult to attack information resources by increasing the work factor of the adversary; it also increases the likelihood of detection. The coordination of allocated controls is essential to ensure that an attack that involves one control does not create adverse, unintended consequences by interfering with other controls. Unintended consequences can include system lockout and cascading alarms. The placement of controls in systems and organizations is an important activity that requires thoughtful analysis. The value of organizational assets is an important consideration in providing additional layering. Defense-in-depth architectural approaches include modularity and layering (see [SA-8(3)](#sa-8.3) ), separation of system and user functionality (see [SC-2](#sc-2) ), and security function isolation (see [SC-3](#sc-3)).

# Parameters

- `pl-08.01_odp.01`
- `pl-08.01_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
