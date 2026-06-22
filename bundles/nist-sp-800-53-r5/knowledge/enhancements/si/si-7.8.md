---
type: control_enhancement
title: SI-7.8 - Auditing Capability for Significant Events
description: 'Upon detection of a potential integrity violation, provide the capability to audit the event and initiate
  the following actions: {{ insert: param, si-07.08_odp.01 }}.'
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
  description: SI-7.8 - Auditing Capability for Significant Events is part of its parent SP 800-53 structure.
- name: SI-7 - Software, Firmware, and Information Integrity
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-7.md
  relation: enhances
  description: SI-7.8 enhances base control SI-7.
nist_id: SI-7.8
sort_id: si-07.08
implementation_level: system
parameter_ids:
- si-07.08_odp.01
- si-07.08_odp.02
- si-07.08_odp.03
reference_links:
- '#si-7'
- '#au-2'
- '#au-6'
- '#au-12'
---

# Summary

Upon detection of a potential integrity violation, provide the capability to audit the event and initiate the following actions: {{ insert: param, si-07.08_odp.01 }}.

# Statement

Upon detection of a potential integrity violation, provide the capability to audit the event and initiate the following actions: {{ insert: param, si-07.08_odp.01 }}.

# Guidance

Organizations select response actions based on types of software, specific software, or information for which there are potential integrity violations.

# Parameters

- `si-07.08_odp.01`
- `si-07.08_odp.02`
- `si-07.08_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
