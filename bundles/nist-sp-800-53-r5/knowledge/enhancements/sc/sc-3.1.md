---
type: control_enhancement
title: SC-3.1 - Hardware Separation
description: Employ hardware separation mechanisms to implement security function isolation.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-3.md
  relation: part_of
  description: SC-3.1 - Hardware Separation is part of its parent SP 800-53 structure.
- name: SC-3 - Security Function Isolation
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-3.md
  relation: enhances
  description: SC-3.1 enhances base control SC-3.
nist_id: SC-3.1
sort_id: sc-03.01
implementation_level: system
parameter_ids: []
reference_links:
- '#sc-3'
---

# Summary

Employ hardware separation mechanisms to implement security function isolation.

# Statement

Employ hardware separation mechanisms to implement security function isolation.

# Guidance

Hardware separation mechanisms include hardware ring architectures that are implemented within microprocessors and hardware-enforced address segmentation used to support logically distinct storage objects with separate attributes (i.e., readable, writeable).

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
