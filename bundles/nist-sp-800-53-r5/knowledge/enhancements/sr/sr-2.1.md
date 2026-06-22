---
type: control_enhancement
title: SR-2.1 - Establish SCRM Team
description: 'Establish a supply chain risk management team consisting of {{ insert: param, sr-02.01_odp.01 }} to
  lead and support the following SCRM activities: {{ insert: param, sr-02.01_odp.02 }}.'
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
- sr
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-2.md
  relation: part_of
  description: SR-2.1 - Establish SCRM Team is part of its parent SP 800-53 structure.
- name: SR-2 - Supply Chain Risk Management Plan
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-2.md
  relation: enhances
  description: SR-2.1 enhances base control SR-2.
nist_id: SR-2.1
sort_id: sr-02.01
implementation_level: organization
parameter_ids:
- sr-02.01_odp.01
- sr-02.01_odp.02
reference_links:
- '#sr-2'
---

# Summary

Establish a supply chain risk management team consisting of {{ insert: param, sr-02.01_odp.01 }} to lead and support the following SCRM activities: {{ insert: param, sr-02.01_odp.02 }}.

# Statement

Establish a supply chain risk management team consisting of {{ insert: param, sr-02.01_odp.01 }} to lead and support the following SCRM activities: {{ insert: param, sr-02.01_odp.02 }}.

# Guidance

To implement supply chain risk management plans, organizations establish a coordinated, team-based approach to identify and assess supply chain risks and manage these risks by using programmatic and technical mitigation techniques. The team approach enables organizations to conduct an analysis of their supply chain, communicate with internal and external partners or stakeholders, and gain broad consensus regarding the appropriate resources for SCRM. The SCRM team consists of organizational personnel with diverse roles and responsibilities for leading and supporting SCRM activities, including risk executive, information technology, contracting, information security, privacy, mission or business, legal, supply chain and logistics, acquisition, business continuity, and other relevant functions. Members of the SCRM team are involved in various aspects of the SDLC and, collectively, have an awareness of and provide expertise in acquisition processes, legal practices, vulnerabilities, threats, and attack vectors, as well as an understanding of the technical aspects and dependencies of systems. The SCRM team can be an extension of the security and privacy risk management processes or be included as part of an organizational risk management team.

# Parameters

- `sr-02.01_odp.01`
- `sr-02.01_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
