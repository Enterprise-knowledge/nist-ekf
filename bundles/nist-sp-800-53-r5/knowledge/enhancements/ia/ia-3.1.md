---
type: control_enhancement
title: IA-3.1 - Cryptographic Bidirectional Authentication
description: 'Authenticate {{ insert: param, ia-03.01_odp.01 }} before establishing {{ insert: param, ia-03.01_odp.02
  }} connection using bidirectional authentication that is cryptographically based.'
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
  description: IA-3.1 - Cryptographic Bidirectional Authentication is part of its parent SP 800-53 structure.
- name: IA-3 - Device Identification and Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-3.md
  relation: enhances
  description: IA-3.1 enhances base control IA-3.
nist_id: IA-3.1
sort_id: ia-03.01
implementation_level: system
parameter_ids:
- ia-03.01_odp.01
- ia-03.01_odp.02
reference_links:
- '#ia-3'
- '#sc-8'
- '#sc-12'
- '#sc-13'
---

# Summary

Authenticate {{ insert: param, ia-03.01_odp.01 }} before establishing {{ insert: param, ia-03.01_odp.02 }} connection using bidirectional authentication that is cryptographically based.

# Statement

Authenticate {{ insert: param, ia-03.01_odp.01 }} before establishing {{ insert: param, ia-03.01_odp.02 }} connection using bidirectional authentication that is cryptographically based.

# Guidance

A local connection is a connection with a device that communicates without the use of a network. A network connection is a connection with a device that communicates through a network. A remote connection is a connection with a device that communicates through an external network. Bidirectional authentication provides stronger protection to validate the identity of other devices for connections that are of greater risk.

# Parameters

- `ia-03.01_odp.01`
- `ia-03.01_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
