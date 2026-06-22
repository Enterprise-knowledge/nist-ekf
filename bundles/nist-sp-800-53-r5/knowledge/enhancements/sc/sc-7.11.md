---
type: control_enhancement
title: SC-7.11 - Restrict Incoming Communications Traffic
description: 'Only allow incoming communications from {{ insert: param, sc-07.11_odp.01 }} to be routed to {{ insert:
  param, sc-07.11_odp.02 }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-7.md
  relation: part_of
  description: SC-7.11 - Restrict Incoming Communications Traffic is part of its parent SP 800-53 structure.
- name: SC-7 - Boundary Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-7.md
  relation: enhances
  description: SC-7.11 enhances base control SC-7.
nist_id: SC-7.11
sort_id: sc-07.11
implementation_level: system
parameter_ids:
- sc-07.11_odp.01
- sc-07.11_odp.02
reference_links:
- '#sc-7'
- '#ac-3'
---

# Summary

Only allow incoming communications from {{ insert: param, sc-07.11_odp.01 }} to be routed to {{ insert: param, sc-07.11_odp.02 }}.

# Statement

Only allow incoming communications from {{ insert: param, sc-07.11_odp.01 }} to be routed to {{ insert: param, sc-07.11_odp.02 }}.

# Guidance

General source address validation techniques are applied to restrict the use of illegal and unallocated source addresses as well as source addresses that should only be used within the system. The restriction of incoming communications traffic provides determinations that source and destination address pairs represent authorized or allowed communications. Determinations can be based on several factors, including the presence of such address pairs in the lists of authorized or allowed communications, the absence of such address pairs in lists of unauthorized or disallowed pairs, or meeting more general rules for authorized or allowed source and destination pairs. Strong authentication of network addresses is not possible without the use of explicit security protocols, and thus, addresses can often be spoofed. Further, identity-based incoming traffic restriction methods can be employed, including router access control lists and firewall rules.

# Parameters

- `sc-07.11_odp.01`
- `sc-07.11_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
