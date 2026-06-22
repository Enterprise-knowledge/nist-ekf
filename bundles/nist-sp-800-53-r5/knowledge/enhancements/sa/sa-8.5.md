---
type: control_enhancement
title: SA-8.5 - Efficiently Mediated Access
description: 'Implement the security design principle of efficiently mediated access in {{ insert: param, sa-08.05_odp
  }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-8.md
  relation: part_of
  description: SA-8.5 - Efficiently Mediated Access is part of its parent SP 800-53 structure.
- name: SA-8 - Security and Privacy Engineering Principles
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-8.md
  relation: enhances
  description: SA-8.5 enhances base control SA-8.
nist_id: SA-8.5
sort_id: sa-08.05
implementation_level: organization
parameter_ids:
- sa-08.05_odp
reference_links:
- '#sa-8'
- '#ac-25'
---

# Summary

Implement the security design principle of efficiently mediated access in {{ insert: param, sa-08.05_odp }}.

# Statement

Implement the security design principle of efficiently mediated access in {{ insert: param, sa-08.05_odp }}.

# Guidance

The principle of efficiently mediated access states that policy enforcement mechanisms utilize the least common mechanism available while satisfying stakeholder requirements within expressed constraints. The mediation of access to system resources (i.e., CPU, memory, devices, communication ports, services, infrastructure, data, and information) is often the predominant security function of secure systems. It also enables the realization of protections for the capability provided to stakeholders by the system. Mediation of resource access can result in performance bottlenecks if the system is not designed correctly. For example, by using hardware mechanisms, efficiently mediated access can be achieved. Once access to a low-level resource such as memory has been obtained, hardware protection mechanisms can ensure that out-of-bounds access does not occur.

# Parameters

- `sa-08.05_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
