---
type: control_enhancement
title: SC-2.2 - Disassociability
description: Store state information from applications and software separately.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-2.md
  relation: part_of
  description: SC-2.2 - Disassociability is part of its parent SP 800-53 structure.
- name: SC-2 - Separation of System and User Functionality
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-2.md
  relation: enhances
  description: SC-2.2 enhances base control SC-2.
nist_id: SC-2.2
sort_id: sc-02.02
implementation_level: system
parameter_ids: []
reference_links:
- '#sc-2'
---

# Summary

Store state information from applications and software separately.

# Statement

Store state information from applications and software separately.

# Guidance

If a system is compromised, storing applications and software separately from state information about users’ interactions with an application may better protect individuals’ privacy.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
