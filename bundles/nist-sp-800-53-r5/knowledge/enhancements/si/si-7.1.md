---
type: control_enhancement
title: SI-7.1 - Integrity Checks
description: 'Perform an integrity check of {{ insert: param, si-7.1_prm_1 }} {{ insert: param, si-7.1_prm_2 }}.'
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
  description: SI-7.1 - Integrity Checks is part of its parent SP 800-53 structure.
- name: SI-7 - Software, Firmware, and Information Integrity
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-7.md
  relation: enhances
  description: SI-7.1 enhances base control SI-7.
nist_id: SI-7.1
sort_id: si-07.01
implementation_level: system
parameter_ids:
- si-7.1_prm_1
- si-7.1_prm_2
- si-7.1_prm_3
- si-7.1_prm_4
- si-07.01_odp.01
- si-07.01_odp.02
- si-07.01_odp.03
- si-07.01_odp.04
- si-07.01_odp.05
- si-07.01_odp.06
- si-07.01_odp.07
- si-07.01_odp.08
- si-07.01_odp.09
- si-07.01_odp.10
- si-07.01_odp.11
- si-07.01_odp.12
reference_links:
- '#si-7'
---

# Summary

Perform an integrity check of {{ insert: param, si-7.1_prm_1 }} {{ insert: param, si-7.1_prm_2 }}.

# Statement

Perform an integrity check of {{ insert: param, si-7.1_prm_1 }} {{ insert: param, si-7.1_prm_2 }}.

# Guidance

Security-relevant events include the identification of new threats to which organizational systems are susceptible and the installation of new hardware, software, or firmware. Transitional states include system startup, restart, shutdown, and abort.

# Parameters

- `si-7.1_prm_1`
- `si-7.1_prm_2`
- `si-7.1_prm_3`
- `si-7.1_prm_4`
- `si-07.01_odp.01`
- `si-07.01_odp.02`
- `si-07.01_odp.03`
- `si-07.01_odp.04`
- `si-07.01_odp.05`
- `si-07.01_odp.06`
- `si-07.01_odp.07`
- `si-07.01_odp.08`
- `si-07.01_odp.09`
- `si-07.01_odp.10`
- `si-07.01_odp.11`
- `si-07.01_odp.12`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
