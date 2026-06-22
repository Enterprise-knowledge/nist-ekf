---
type: control_enhancement
title: SI-7.9 - Verify Boot Process
description: 'Verify the integrity of the boot process of the following system components: {{ insert: param, si-07.09_odp
  }}.'
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
  description: SI-7.9 - Verify Boot Process is part of its parent SP 800-53 structure.
- name: SI-7 - Software, Firmware, and Information Integrity
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-7.md
  relation: enhances
  description: SI-7.9 enhances base control SI-7.
nist_id: SI-7.9
sort_id: si-07.09
implementation_level: system
parameter_ids:
- si-07.09_odp
reference_links:
- '#si-7'
- '#si-6'
---

# Summary

Verify the integrity of the boot process of the following system components: {{ insert: param, si-07.09_odp }}.

# Statement

Verify the integrity of the boot process of the following system components: {{ insert: param, si-07.09_odp }}.

# Guidance

Ensuring the integrity of boot processes is critical to starting system components in known, trustworthy states. Integrity verification mechanisms provide a level of assurance that only trusted code is executed during boot processes.

# Parameters

- `si-07.09_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
