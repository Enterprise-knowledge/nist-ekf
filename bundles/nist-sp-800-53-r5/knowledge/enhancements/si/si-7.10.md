---
type: control_enhancement
title: SI-7.10 - Protection of Boot Firmware
description: 'Implement the following mechanisms to protect the integrity of boot firmware in {{ insert: param,
  si-07.10_odp.02 }}: {{ insert: param, si-07.10_odp.01 }}.'
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
- si
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-7.md
  relation: part_of
  description: SI-7.10 - Protection of Boot Firmware is part of its parent SP 800-53 structure.
- name: SI-7 - Software, Firmware, and Information Integrity
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-7.md
  relation: enhances
  description: SI-7.10 enhances base control SI-7.
nist_id: SI-7.10
sort_id: si-07.10
implementation_level: system
parameter_ids:
- si-07.10_odp.01
- si-07.10_odp.02
reference_links:
- '#si-7'
- '#si-6'
---

# Summary

Implement the following mechanisms to protect the integrity of boot firmware in {{ insert: param, si-07.10_odp.02 }}: {{ insert: param, si-07.10_odp.01 }}.

# Statement

Implement the following mechanisms to protect the integrity of boot firmware in {{ insert: param, si-07.10_odp.02 }}: {{ insert: param, si-07.10_odp.01 }}.

# Guidance

Unauthorized modifications to boot firmware may indicate a sophisticated, targeted attack. These types of targeted attacks can result in a permanent denial of service or a persistent malicious code presence. These situations can occur if the firmware is corrupted or if the malicious code is embedded within the firmware. System components can protect the integrity of boot firmware in organizational systems by verifying the integrity and authenticity of all updates to the firmware prior to applying changes to the system component and preventing unauthorized processes from modifying the boot firmware.

# Parameters

- `si-07.10_odp.01`
- `si-07.10_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
