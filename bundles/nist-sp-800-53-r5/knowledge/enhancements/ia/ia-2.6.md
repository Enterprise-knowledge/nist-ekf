---
type: control_enhancement
title: IA-2.6 - Access to Accounts —separate Device
description: 'Implement multi-factor authentication for {{ insert: param, ia-02.06_odp.01 }} access to {{ insert:
  param, ia-02.06_odp.02 }} such that:'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-2.md
  relation: part_of
  description: IA-2.6 - Access to Accounts —separate Device is part of its parent SP 800-53 structure.
- name: IA-2 - Identification and Authentication (Organizational Users)
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-2.md
  relation: enhances
  description: IA-2.6 enhances base control IA-2.
nist_id: IA-2.6
sort_id: ia-02.06
implementation_level: system
parameter_ids:
- ia-02.06_odp.01
- ia-02.06_odp.02
- ia-02.06_odp.03
reference_links:
- '#ia-2'
- '#ac-6'
---

# Summary

Implement multi-factor authentication for {{ insert: param, ia-02.06_odp.01 }} access to {{ insert: param, ia-02.06_odp.02 }} such that:

# Statement

Implement multi-factor authentication for {{ insert: param, ia-02.06_odp.01 }} access to {{ insert: param, ia-02.06_odp.02 }} such that:

# Guidance

The purpose of requiring a device that is separate from the system to which the user is attempting to gain access for one of the factors during multi-factor authentication is to reduce the likelihood of compromising authenticators or credentials stored on the system. Adversaries may be able to compromise such authenticators or credentials and subsequently impersonate authorized users. Implementing one of the factors on a separate device (e.g., a hardware token), provides a greater strength of mechanism and an increased level of assurance in the authentication process.

# Parameters

- `ia-02.06_odp.01`
- `ia-02.06_odp.02`
- `ia-02.06_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
