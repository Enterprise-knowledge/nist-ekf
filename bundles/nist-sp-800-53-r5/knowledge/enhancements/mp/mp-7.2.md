---
type: control_enhancement
title: MP-7.2 - Prohibit Use of Sanitization-resistant Media
description: Prohibit the use of sanitization-resistant media in organizational systems.
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
- mp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-7.md
  relation: part_of
  description: MP-7.2 - Prohibit Use of Sanitization-resistant Media is part of its parent SP 800-53 structure.
- name: MP-7 - Media Use
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-7.md
  relation: enhances
  description: MP-7.2 enhances base control MP-7.
nist_id: MP-7.2
sort_id: mp-07.02
implementation_level: organization
parameter_ids: []
reference_links:
- '#mp-7'
- '#mp-6'
---

# Summary

Prohibit the use of sanitization-resistant media in organizational systems.

# Statement

Prohibit the use of sanitization-resistant media in organizational systems.

# Guidance

Sanitization resistance refers to how resistant media are to non-destructive sanitization techniques with respect to the capability to purge information from media. Certain types of media do not support sanitization commands, or if supported, the interfaces are not supported in a standardized way across these devices. Sanitization-resistant media includes compact flash, embedded flash on boards and devices, solid state drives, and USB removable media.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
