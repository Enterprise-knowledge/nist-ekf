---
type: control_enhancement
title: AC-6.1 - Authorize Access to Security Functions
description: 'Authorize access for {{ insert: param, ac-06.01_odp.01 }} to:'
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
- ac
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-6.md
  relation: part_of
  description: AC-6.1 - Authorize Access to Security Functions is part of its parent SP 800-53 structure.
- name: AC-6 - Least Privilege
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-6.md
  relation: enhances
  description: AC-6.1 enhances base control AC-6.
nist_id: AC-6.1
sort_id: ac-06.01
implementation_level: organization
parameter_ids:
- ac-6.1_prm_2
- ac-06.01_odp.01
- ac-06.01_odp.02
- ac-06.01_odp.03
- ac-06.01_odp.04
- ac-06.01_odp.05
reference_links:
- '#ac-6'
- '#ac-17'
- '#ac-18'
- '#ac-19'
- '#au-9'
- '#pe-2'
---

# Summary

Authorize access for {{ insert: param, ac-06.01_odp.01 }} to:

# Statement

Authorize access for {{ insert: param, ac-06.01_odp.01 }} to:

# Guidance

Security functions include establishing system accounts, configuring access authorizations (i.e., permissions, privileges), configuring settings for events to be audited, and establishing intrusion detection parameters. Security-relevant information includes filtering rules for routers or firewalls, configuration parameters for security services, cryptographic key management information, and access control lists. Authorized personnel include security administrators, system administrators, system security officers, system programmers, and other privileged users.

# Parameters

- `ac-6.1_prm_2`
- `ac-06.01_odp.01`
- `ac-06.01_odp.02`
- `ac-06.01_odp.03`
- `ac-06.01_odp.04`
- `ac-06.01_odp.05`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
