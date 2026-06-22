---
type: control
title: PL-8 - Security and Privacy Architectures
description: SP 800-53 control PL-8.
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
- pl
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/pl.md
  relation: part_of
  description: PL-8 - Security and Privacy Architectures is part of its parent SP 800-53 structure.
- name: PL-8.1 - Defense in Depth
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pl/pl-8.1.md
  relation: has_enhancement
  description: PL-8 has enhancement PL-8.1.
- name: PL-8.2 - Supplier Diversity
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pl/pl-8.2.md
  relation: has_enhancement
  description: PL-8 has enhancement PL-8.2.
nist_id: PL-8
sort_id: pl-08
implementation_level: organization
parameter_ids:
- pl-08_odp
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#e3cc0520-a366-4fc9-abc2-5272db7e3564'
- '#61ccf0f4-d3e7-42db-9796-ce6cb1c85989'
- '#cm-2'
- '#cm-6'
- '#pl-2'
- '#pl-7'
- '#pl-9'
- '#pm-5'
- '#pm-7'
- '#ra-9'
- '#sa-3'
- '#sa-5'
- '#sa-8'
- '#sa-17'
- '#sc-7'
---

# Summary

SP 800-53 control PL-8.

# Statement

No statement text was present in the OSCAL record.

# Guidance

The security and privacy architectures at the system level are consistent with the organization-wide security and privacy architectures described in [PM-7](#pm-7) , which are integral to and developed as part of the enterprise architecture. The architectures include an architectural description, the allocation of security and privacy functionality (including controls), security- and privacy-related information for external interfaces, information being exchanged across the interfaces, and the protection mechanisms associated with each interface. The architectures can also include other information, such as user roles and the access privileges assigned to each role; security and privacy requirements; types of information processed, stored, and transmitted by the system; supply chain risk management requirements; restoration priorities of information and system services; and other protection needs.

[SP 800-160-1](#e3cc0520-a366-4fc9-abc2-5272db7e3564) provides guidance on the use of security architectures as part of the system development life cycle process. [OMB M-19-03](#c5e11048-1d38-4af3-b00b-0d88dc26860c) requires the use of the systems security engineering concepts described in [SP 800-160-1](#e3cc0520-a366-4fc9-abc2-5272db7e3564) for high value assets. Security and privacy architectures are reviewed and updated throughout the system development life cycle, from analysis of alternatives through review of the proposed architecture in the RFP responses to the design reviews before and during implementation (e.g., during preliminary design reviews and critical design reviews).

In today’s modern computing architectures, it is becoming less common for organizations to control all information resources. There may be key dependencies on external information services and service providers. Describing such dependencies in the security and privacy architectures is necessary for developing a comprehensive mission and business protection strategy. Establishing, developing, documenting, and maintaining under configuration control a baseline configuration for organizational systems is critical to implementing and maintaining effective architectures. The development of the architectures is coordinated with the senior agency information security officer and the senior agency official for privacy to ensure that the controls needed to support security and privacy requirements are identified and effectively implemented. In many circumstances, there may be no distinction between the security and privacy architecture for a system. In other circumstances, security objectives may be adequately satisfied, but privacy objectives may only be partially satisfied by the security requirements. In these cases, consideration of the privacy requirements needed to achieve satisfaction will result in a distinct privacy architecture. The documentation, however, may simply reflect the combined architectures.

[PL-8](#pl-8) is primarily directed at organizations to ensure that architectures are developed for the system and, moreover, that the architectures are integrated with or tightly coupled to the enterprise architecture. In contrast, [SA-17](#sa-17) is primarily directed at the external information technology product and system developers and integrators. [SA-17](#sa-17) , which is complementary to [PL-8](#pl-8) , is selected when organizations outsource the development of systems or components to external entities and when there is a need to demonstrate consistency with the organization’s enterprise architecture and security and privacy architectures.

# Parameters

- `pl-08_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
