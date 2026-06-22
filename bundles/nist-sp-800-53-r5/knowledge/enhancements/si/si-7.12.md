---
type: control_enhancement
title: SI-7.12 - Integrity Verification
description: 'Require that the integrity of the following user-installed software be verified prior to execution:
  {{ insert: param, si-07.12_odp }}.'
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
  description: SI-7.12 - Integrity Verification is part of its parent SP 800-53 structure.
- name: SI-7 - Software, Firmware, and Information Integrity
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-7.md
  relation: enhances
  description: SI-7.12 enhances base control SI-7.
nist_id: SI-7.12
sort_id: si-07.12
implementation_level: organization
parameter_ids:
- si-07.12_odp
reference_links:
- '#si-7'
- '#si-2'
- '#cm-11'
- '#fe209006-bfd4-4033-a79a-9fee1adaf372'
---

# Summary

Require that the integrity of the following user-installed software be verified prior to execution: {{ insert: param, si-07.12_odp }}.

# Statement

Require that the integrity of the following user-installed software be verified prior to execution: {{ insert: param, si-07.12_odp }}.

# Guidance

Organizations verify the integrity of user-installed software prior to execution to reduce the likelihood of executing malicious code or programs that contains errors from unauthorized modifications. Organizations consider the source of the software, ensuring the software and updates come from authorized sources and/or sites, and the practicality of approaches to verifying software integrity, including the availability of trustworthy checksums from software developers and vendors.

# Parameters

- `si-07.12_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
