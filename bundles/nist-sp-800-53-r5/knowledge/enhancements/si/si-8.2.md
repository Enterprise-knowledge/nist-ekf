---
type: control_enhancement
title: SI-8.2 - Automatic Updates
description: 'Automatically update spam protection mechanisms {{ insert: param, si-08.02_odp }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-8.md
  relation: part_of
  description: SI-8.2 - Automatic Updates is part of its parent SP 800-53 structure.
- name: SI-8 - Spam Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-8.md
  relation: enhances
  description: SI-8.2 enhances base control SI-8.
nist_id: SI-8.2
sort_id: si-08.02
implementation_level: system
parameter_ids:
- si-08.02_odp
reference_links:
- '#si-8'
---

# Summary

Automatically update spam protection mechanisms {{ insert: param, si-08.02_odp }}.

# Statement

Automatically update spam protection mechanisms {{ insert: param, si-08.02_odp }}.

# Guidance

Using automated mechanisms to update spam protection mechanisms helps to ensure that updates occur on a regular basis and provide the latest content and protection capabilities.

# Parameters

- `si-08.02_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
