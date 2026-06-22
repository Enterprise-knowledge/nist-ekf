---
type: control_enhancement
title: SI-3.8 - Detect Unauthorized Commands
description: SP 800-53 control SI-3.8.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-3.md
  relation: part_of
  description: SI-3.8 - Detect Unauthorized Commands is part of its parent SP 800-53 structure.
- name: SI-3 - Malicious Code Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-3.md
  relation: enhances
  description: SI-3.8 enhances base control SI-3.
nist_id: SI-3.8
sort_id: si-03.08
implementation_level: system
parameter_ids:
- si-03.08_odp.01
- si-03.08_odp.02
- si-03.08_odp.03
reference_links:
- '#si-3'
- '#au-2'
- '#au-6'
- '#au-12'
---

# Summary

SP 800-53 control SI-3.8.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Detecting unauthorized commands can be applied to critical interfaces other than kernel-based interfaces, including interfaces with virtual machines and privileged applications. Unauthorized operating system commands include commands for kernel functions from system processes that are not trusted to initiate such commands as well as commands for kernel functions that are suspicious even though commands of that type are reasonable for processes to initiate. Organizations can define the malicious commands to be detected by a combination of command types, command classes, or specific instances of commands. Organizations can also define hardware components by component type, component, component location in the network, or a combination thereof. Organizations may select different actions for different types, classes, or instances of malicious commands.

# Parameters

- `si-03.08_odp.01`
- `si-03.08_odp.02`
- `si-03.08_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
