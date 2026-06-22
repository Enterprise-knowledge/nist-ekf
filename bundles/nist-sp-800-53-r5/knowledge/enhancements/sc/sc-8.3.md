---
type: control_enhancement
title: SC-8.3 - Cryptographic Protection for Message Externals
description: 'Implement cryptographic mechanisms to protect message externals unless otherwise protected by {{ insert:
  param, sc-08.03_odp }}.'
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
  description: SC-8.3 - Cryptographic Protection for Message Externals is part of its parent SP 800-53 structure.
- name: SC-8 - Transmission Confidentiality and Integrity
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-8.md
  relation: enhances
  description: SC-8.3 enhances base control SC-8.
nist_id: SC-8.3
sort_id: sc-08.03
implementation_level: system
parameter_ids:
- sc-08.03_odp
reference_links:
- '#sc-8'
- '#sc-12'
- '#sc-13'
---

# Summary

Implement cryptographic mechanisms to protect message externals unless otherwise protected by {{ insert: param, sc-08.03_odp }}.

# Statement

Implement cryptographic mechanisms to protect message externals unless otherwise protected by {{ insert: param, sc-08.03_odp }}.

# Guidance

Cryptographic protection for message externals addresses protection from the unauthorized disclosure of information. Message externals include message headers and routing information. Cryptographic protection prevents the exploitation of message externals and applies to internal and external networks or links that may be visible to individuals who are not authorized users. Header and routing information is sometimes transmitted in clear text (i.e., unencrypted) because the information is not identified by organizations as having significant value or because encrypting the information can result in lower network performance or higher costs. Alternative physical controls include protected distribution systems.

# Parameters

- `sc-08.03_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
