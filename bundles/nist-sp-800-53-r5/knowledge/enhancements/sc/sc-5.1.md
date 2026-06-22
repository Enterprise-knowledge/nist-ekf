---
type: control_enhancement
title: SC-5.1 - Restrict Ability to Attack Other Systems
description: 'Restrict the ability of individuals to launch the following denial-of-service attacks against other
  systems: {{ insert: param, sc-05.01_odp }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-5.md
  relation: part_of
  description: SC-5.1 - Restrict Ability to Attack Other Systems is part of its parent SP 800-53 structure.
- name: SC-5 - Denial-of-service Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-5.md
  relation: enhances
  description: SC-5.1 enhances base control SC-5.
nist_id: SC-5.1
sort_id: sc-05.01
implementation_level: system
parameter_ids:
- sc-05.01_odp
reference_links:
- '#sc-5'
---

# Summary

Restrict the ability of individuals to launch the following denial-of-service attacks against other systems: {{ insert: param, sc-05.01_odp }}.

# Statement

Restrict the ability of individuals to launch the following denial-of-service attacks against other systems: {{ insert: param, sc-05.01_odp }}.

# Guidance

Restricting the ability of individuals to launch denial-of-service attacks requires the mechanisms commonly used for such attacks to be unavailable. Individuals of concern include hostile insiders or external adversaries who have breached or compromised the system and are using it to launch a denial-of-service attack. Organizations can restrict the ability of individuals to connect and transmit arbitrary information on the transport medium (i.e., wired networks, wireless networks, spoofed Internet protocol packets). Organizations can also limit the ability of individuals to use excessive system resources. Protection against individuals having the ability to launch denial-of-service attacks may be implemented on specific systems or boundary devices that prohibit egress to potential target systems.

# Parameters

- `sc-05.01_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
