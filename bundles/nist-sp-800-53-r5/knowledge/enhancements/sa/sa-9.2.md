---
type: control_enhancement
title: SA-9.2 - Identification of Functions, Ports, Protocols, and Services
description: 'Require providers of the following external system services to identify the functions, ports, protocols,
  and other services required for the use of such services: {{ insert: param, sa-09.02_odp }}.'
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
- sa
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-9.md
  relation: part_of
  description: SA-9.2 - Identification of Functions, Ports, Protocols, and Services is part of its parent SP 800-53
    structure.
- name: SA-9 - External System Services
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-9.md
  relation: enhances
  description: SA-9.2 enhances base control SA-9.
nist_id: SA-9.2
sort_id: sa-09.02
implementation_level: organization
parameter_ids:
- sa-09.02_odp
reference_links:
- '#sa-9'
- '#cm-6'
- '#cm-7'
---

# Summary

Require providers of the following external system services to identify the functions, ports, protocols, and other services required for the use of such services: {{ insert: param, sa-09.02_odp }}.

# Statement

Require providers of the following external system services to identify the functions, ports, protocols, and other services required for the use of such services: {{ insert: param, sa-09.02_odp }}.

# Guidance

Information from external service providers regarding the specific functions, ports, protocols, and services used in the provision of such services can be useful when the need arises to understand the trade-offs involved in restricting certain functions and services or blocking certain ports and protocols.

# Parameters

- `sa-09.02_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
