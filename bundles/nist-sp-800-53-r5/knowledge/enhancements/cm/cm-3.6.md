---
type: control_enhancement
title: CM-3.6 - Cryptography Management
description: 'Ensure that cryptographic mechanisms used to provide the following controls are under configuration
  management: {{ insert: param, cm-03.06_odp }}.'
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
- cm
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-3.md
  relation: part_of
  description: CM-3.6 - Cryptography Management is part of its parent SP 800-53 structure.
- name: CM-3 - Configuration Change Control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-3.md
  relation: enhances
  description: CM-3.6 enhances base control CM-3.
nist_id: CM-3.6
sort_id: cm-03.06
implementation_level: organization
parameter_ids:
- cm-03.06_odp
reference_links:
- '#cm-3'
- '#sc-12'
---

# Summary

Ensure that cryptographic mechanisms used to provide the following controls are under configuration management: {{ insert: param, cm-03.06_odp }}.

# Statement

Ensure that cryptographic mechanisms used to provide the following controls are under configuration management: {{ insert: param, cm-03.06_odp }}.

# Guidance

The controls referenced in the control enhancement refer to security and privacy controls from the control catalog. Regardless of the cryptographic mechanisms employed, processes and procedures are in place to manage those mechanisms. For example, if system components use certificates for identification and authentication, a process is implemented to address the expiration of those certificates.

# Parameters

- `cm-03.06_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
