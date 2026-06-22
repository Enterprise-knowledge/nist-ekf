---
type: control_enhancement
title: SI-7.7 - Integration of Detection and Response
description: 'Incorporate the detection of the following unauthorized changes into the organizational incident response
  capability: {{ insert: param, si-07.07_odp }}.'
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
  description: SI-7.7 - Integration of Detection and Response is part of its parent SP 800-53 structure.
- name: SI-7 - Software, Firmware, and Information Integrity
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-7.md
  relation: enhances
  description: SI-7.7 enhances base control SI-7.
nist_id: SI-7.7
sort_id: si-07.07
implementation_level: organization
parameter_ids:
- si-07.07_odp
reference_links:
- '#si-7'
- '#au-2'
- '#au-6'
- '#ir-4'
- '#ir-5'
- '#si-4'
---

# Summary

Incorporate the detection of the following unauthorized changes into the organizational incident response capability: {{ insert: param, si-07.07_odp }}.

# Statement

Incorporate the detection of the following unauthorized changes into the organizational incident response capability: {{ insert: param, si-07.07_odp }}.

# Guidance

Integrating detection and response helps to ensure that detected events are tracked, monitored, corrected, and available for historical purposes. Maintaining historical records is important for being able to identify and discern adversary actions over an extended time period and for possible legal actions. Security-relevant changes include unauthorized changes to established configuration settings or the unauthorized elevation of system privileges.

# Parameters

- `si-07.07_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
