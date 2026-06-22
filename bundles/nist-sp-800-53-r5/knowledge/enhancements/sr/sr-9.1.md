---
type: control_enhancement
title: SR-9.1 - Multiple Stages of System Development Life Cycle
description: Employ anti-tamper technologies, tools, and techniques throughout the system development life cycle.
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
- sr
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-9.md
  relation: part_of
  description: SR-9.1 - Multiple Stages of System Development Life Cycle is part of its parent SP 800-53 structure.
- name: SR-9 - Tamper Resistance and Detection
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-9.md
  relation: enhances
  description: SR-9.1 enhances base control SR-9.
nist_id: SR-9.1
sort_id: sr-09.01
implementation_level: organization
parameter_ids: []
reference_links:
- '#sr-9'
- '#sa-3'
---

# Summary

Employ anti-tamper technologies, tools, and techniques throughout the system development life cycle.

# Statement

Employ anti-tamper technologies, tools, and techniques throughout the system development life cycle.

# Guidance

The system development life cycle includes research and development, design, manufacturing, acquisition, delivery, integration, operations and maintenance, and disposal. Organizations use a combination of hardware and software techniques for tamper resistance and detection. Organizations use obfuscation and self-checking to make reverse engineering and modifications more difficult, time-consuming, and expensive for adversaries. The customization of systems and system components can make substitutions easier to detect and therefore limit damage.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
