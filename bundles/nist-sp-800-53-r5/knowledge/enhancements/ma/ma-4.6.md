---
type: control_enhancement
title: MA-4.6 - Cryptographic Protection
description: 'Implement the following cryptographic mechanisms to protect the integrity and confidentiality of nonlocal
  maintenance and diagnostic communications: {{ insert: param, ma-04.06_odp }}.'
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
- ma
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-4.md
  relation: part_of
  description: MA-4.6 - Cryptographic Protection is part of its parent SP 800-53 structure.
- name: MA-4 - Nonlocal Maintenance
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-4.md
  relation: enhances
  description: MA-4.6 enhances base control MA-4.
nist_id: MA-4.6
sort_id: ma-04.06
implementation_level: organization
parameter_ids:
- ma-04.06_odp
reference_links:
- '#ma-4'
- '#sc-8'
- '#sc-12'
- '#sc-13'
---

# Summary

Implement the following cryptographic mechanisms to protect the integrity and confidentiality of nonlocal maintenance and diagnostic communications: {{ insert: param, ma-04.06_odp }}.

# Statement

Implement the following cryptographic mechanisms to protect the integrity and confidentiality of nonlocal maintenance and diagnostic communications: {{ insert: param, ma-04.06_odp }}.

# Guidance

Failure to protect nonlocal maintenance and diagnostic communications can result in unauthorized individuals gaining access to organizational information. Unauthorized access during remote maintenance sessions can result in a variety of hostile actions, including malicious code insertion, unauthorized changes to system parameters, and exfiltration of organizational information. Such actions can result in the loss or degradation of mission or business capabilities.

# Parameters

- `ma-04.06_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
