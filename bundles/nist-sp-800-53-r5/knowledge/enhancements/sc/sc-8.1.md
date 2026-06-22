---
type: control_enhancement
title: SC-8.1 - Cryptographic Protection
description: 'Implement cryptographic mechanisms to {{ insert: param, sc-08.01_odp }} during transmission.'
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
- sc
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-8.md
  relation: part_of
  description: SC-8.1 - Cryptographic Protection is part of its parent SP 800-53 structure.
- name: SC-8 - Transmission Confidentiality and Integrity
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-8.md
  relation: enhances
  description: SC-8.1 enhances base control SC-8.
nist_id: SC-8.1
sort_id: sc-08.01
implementation_level: system
parameter_ids:
- sc-08.01_odp
reference_links:
- '#sc-8'
- '#sc-12'
- '#sc-13'
---

# Summary

Implement cryptographic mechanisms to {{ insert: param, sc-08.01_odp }} during transmission.

# Statement

Implement cryptographic mechanisms to {{ insert: param, sc-08.01_odp }} during transmission.

# Guidance

Encryption protects information from unauthorized disclosure and modification during transmission. Cryptographic mechanisms that protect the confidentiality and integrity of information during transmission include TLS and IPSec. Cryptographic mechanisms used to protect information integrity include cryptographic hash functions that have applications in digital signatures, checksums, and message authentication codes.

# Parameters

- `sc-08.01_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
