---
type: control_enhancement
title: IA-3.4 - Device Attestation
description: 'Handle device identification and authentication based on attestation by {{ insert: param, ia-03.04_odp
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
- ia
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-3.md
  relation: part_of
  description: IA-3.4 - Device Attestation is part of its parent SP 800-53 structure.
- name: IA-3 - Device Identification and Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-3.md
  relation: enhances
  description: IA-3.4 enhances base control IA-3.
nist_id: IA-3.4
sort_id: ia-03.04
implementation_level: organization
parameter_ids:
- ia-03.04_odp
reference_links:
- '#ia-3'
- '#cm-2'
- '#cm-3'
- '#cm-6'
---

# Summary

Handle device identification and authentication based on attestation by {{ insert: param, ia-03.04_odp }}.

# Statement

Handle device identification and authentication based on attestation by {{ insert: param, ia-03.04_odp }}.

# Guidance

Device attestation refers to the identification and authentication of a device based on its configuration and known operating state. Device attestation can be determined via a cryptographic hash of the device. If device attestation is the means of identification and authentication, then it is important that patches and updates to the device are handled via a configuration management process such that the patches and updates are done securely and do not disrupt identification and authentication to other devices.

# Parameters

- `ia-03.04_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
