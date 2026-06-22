---
type: control_enhancement
title: SI-4.18 - Analyze Traffic and Covert Exfiltration
description: 'Analyze outbound communications traffic at external interfaces to the system and at the following
  interior points to detect covert exfiltration of information: {{ insert: param, si-04.18_odp }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-4.md
  relation: part_of
  description: SI-4.18 - Analyze Traffic and Covert Exfiltration is part of its parent SP 800-53 structure.
- name: SI-4 - System Monitoring
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-4.md
  relation: enhances
  description: SI-4.18 enhances base control SI-4.
nist_id: SI-4.18
sort_id: si-04.18
implementation_level: organization
parameter_ids:
- si-04.18_odp
reference_links:
- '#si-4'
---

# Summary

Analyze outbound communications traffic at external interfaces to the system and at the following interior points to detect covert exfiltration of information: {{ insert: param, si-04.18_odp }}.

# Statement

Analyze outbound communications traffic at external interfaces to the system and at the following interior points to detect covert exfiltration of information: {{ insert: param, si-04.18_odp }}.

# Guidance

Organization-defined interior points include subnetworks and subsystems. Covert means that can be used to exfiltrate information include steganography.

# Parameters

- `si-04.18_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
