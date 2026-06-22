---
type: control
title: IA-3 - Device Identification and Authentication
description: 'Uniquely identify and authenticate {{ insert: param, ia-03_odp.01 }} before establishing a {{ insert:
  param, ia-03_odp.02 }} connection.'
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ia.md
  relation: part_of
  description: IA-3 - Device Identification and Authentication is part of its parent SP 800-53 structure.
- name: IA-3.1 - Cryptographic Bidirectional Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-3.1.md
  relation: has_enhancement
  description: IA-3 has enhancement IA-3.1.
- name: IA-3.2 - Cryptographic Bidirectional Network Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-3.2.md
  relation: has_enhancement
  description: IA-3 has enhancement IA-3.2.
- name: IA-3.3 - Dynamic Address Allocation
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-3.3.md
  relation: has_enhancement
  description: IA-3 has enhancement IA-3.3.
- name: IA-3.4 - Device Attestation
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ia/ia-3.4.md
  relation: has_enhancement
  description: IA-3 has enhancement IA-3.4.
nist_id: IA-3
sort_id: ia-03
implementation_level: system
parameter_ids:
- ia-03_odp.01
- ia-03_odp.02
reference_links:
- '#ac-17'
- '#ac-18'
- '#ac-19'
- '#au-6'
- '#ca-3'
- '#ca-9'
- '#ia-4'
- '#ia-5'
- '#ia-9'
- '#ia-11'
- '#ia-13'
- '#si-4'
---

# Summary

Uniquely identify and authenticate {{ insert: param, ia-03_odp.01 }} before establishing a {{ insert: param, ia-03_odp.02 }} connection.

# Statement

Uniquely identify and authenticate {{ insert: param, ia-03_odp.01 }} before establishing a {{ insert: param, ia-03_odp.02 }} connection.

# Guidance

Devices that require unique device-to-device identification and authentication are defined by type, device, or a combination of type and device. Organization-defined device types include devices that are not owned by the organization. Systems use shared known information (e.g., Media Access Control [MAC], Transmission Control Protocol/Internet Protocol [TCP/IP] addresses) for device identification or organizational authentication solutions (e.g., Institute of Electrical and Electronics Engineers (IEEE) 802.1x and Extensible Authentication Protocol [EAP], RADIUS server with EAP-Transport Layer Security [TLS] authentication, Kerberos) to identify and authenticate devices on local and wide area networks. Organizations determine the required strength of authentication mechanisms based on the security categories of systems and mission or business requirements. Because of the challenges of implementing device authentication on a large scale, organizations can restrict the application of the control to a limited number/type of devices based on mission or business needs.

# Parameters

- `ia-03_odp.01`
- `ia-03_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
