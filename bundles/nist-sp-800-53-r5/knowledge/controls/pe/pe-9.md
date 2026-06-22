---
type: control
title: PE-9 - Power Equipment and Cabling
description: Protect power equipment and power cabling for the system from damage and destruction.
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
- pe
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/pe.md
  relation: part_of
  description: PE-9 - Power Equipment and Cabling is part of its parent SP 800-53 structure.
- name: PE-9.1 - Redundant Cabling
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-9.1.md
  relation: has_enhancement
  description: PE-9 has enhancement PE-9.1.
- name: PE-9.2 - Automatic Voltage Controls
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-9.2.md
  relation: has_enhancement
  description: PE-9 has enhancement PE-9.2.
nist_id: PE-9
sort_id: pe-09
implementation_level: organization
parameter_ids: []
reference_links:
- '#pe-4'
---

# Summary

Protect power equipment and power cabling for the system from damage and destruction.

# Statement

Protect power equipment and power cabling for the system from damage and destruction.

# Guidance

Organizations determine the types of protection necessary for the power equipment and cabling employed at different locations that are both internal and external to organizational facilities and environments of operation. Types of power equipment and cabling include internal cabling and uninterruptable power sources in offices or data centers, generators and power cabling outside of buildings, and power sources for self-contained components such as satellites, vehicles, and other deployable systems.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
