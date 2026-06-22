---
type: control
title: SR-7 - Supply Chain Operations Security
description: 'Employ the following Operations Security (OPSEC) controls to protect supply chain-related information
  for the system, system component, or system service: {{ insert: param, sr-07_odp }}.'
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/sr.md
  relation: part_of
  description: SR-7 - Supply Chain Operations Security is part of its parent SP 800-53 structure.
nist_id: SR-7
sort_id: sr-07
implementation_level: organization
parameter_ids:
- sr-07_odp
reference_links:
- '#21caa535-1154-4369-ba7b-32c309fee0f7'
- '#08b07465-dbdc-48d6-8a0b-37279602ac16'
- '#863caf2a-978a-4260-9e8d-4a8929bce40c'
- '#e8e84963-14fc-4c3a-be05-b412a5d37cd2'
- '#e24b06cc-9129-4998-a76a-65c3d7a576ba'
- '#sc-38'
---

# Summary

Employ the following Operations Security (OPSEC) controls to protect supply chain-related information for the system, system component, or system service: {{ insert: param, sr-07_odp }}.

# Statement

Employ the following Operations Security (OPSEC) controls to protect supply chain-related information for the system, system component, or system service: {{ insert: param, sr-07_odp }}.

# Guidance

Supply chain OPSEC expands the scope of OPSEC to include suppliers and potential suppliers. OPSEC is a process that includes identifying critical information, analyzing friendly actions related to operations and other activities to identify actions that can be observed by potential adversaries, determining indicators that potential adversaries might obtain that could be interpreted or pieced together to derive information in sufficient time to cause harm to organizations, implementing safeguards or countermeasures to eliminate or reduce exploitable vulnerabilities and risk to an acceptable level, and considering how aggregated information may expose users or specific uses of the supply chain. Supply chain information includes user identities; uses for systems, system components, and system services; supplier identities; security and privacy requirements; system and component configurations; supplier processes; design specifications; and testing and evaluation results. Supply chain OPSEC may require organizations to withhold mission or business information from suppliers and may include the use of intermediaries to hide the end use or users of systems, system components, or system services.

# Parameters

- `sr-07_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
