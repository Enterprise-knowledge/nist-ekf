---
type: control
title: PM-7 - Enterprise Architecture
description: Develop and maintain an enterprise architecture with consideration for information security, privacy,
  and the resulting risk to organizational operations and assets, individuals, other organizations, and the Nation.
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
- pm
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/pm.md
  relation: part_of
  description: PM-7 - Enterprise Architecture is part of its parent SP 800-53 structure.
- name: PM-7.1 - Offloading
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pm/pm-7.1.md
  relation: has_enhancement
  description: PM-7 has enhancement PM-7.1.
nist_id: PM-7
sort_id: pm-07
implementation_level: organization
parameter_ids: []
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#482e4c99-9dc4-41ad-bba8-0f3f0032c1f8'
- '#cec037f3-8aba-4c97-84b4-4082f9e515d2'
- '#e3cc0520-a366-4fc9-abc2-5272db7e3564'
- '#61ccf0f4-d3e7-42db-9796-ce6cb1c85989'
- '#au-6'
- '#pl-2'
- '#pl-8'
- '#pm-11'
- '#ra-2'
- '#sa-3'
- '#sa-8'
- '#sa-17'
---

# Summary

Develop and maintain an enterprise architecture with consideration for information security, privacy, and the resulting risk to organizational operations and assets, individuals, other organizations, and the Nation.

# Statement

Develop and maintain an enterprise architecture with consideration for information security, privacy, and the resulting risk to organizational operations and assets, individuals, other organizations, and the Nation.

# Guidance

The integration of security and privacy requirements and controls into the enterprise architecture helps to ensure that security and privacy considerations are addressed throughout the system development life cycle and are explicitly related to the organization’s mission and business processes. The process of security and privacy requirements integration also embeds into the enterprise architecture and the organization’s security and privacy architectures consistent with the organizational risk management strategy. For PM-7, security and privacy architectures are developed at a system-of-systems level, representing all organizational systems. For [PL-8](#pl-8) , the security and privacy architectures are developed at a level that represents an individual system. The system-level architectures are consistent with the security and privacy architectures defined for the organization. Security and privacy requirements and control integration are most effectively accomplished through the rigorous application of the Risk Management Framework [SP 800-37](#482e4c99-9dc4-41ad-bba8-0f3f0032c1f8) and supporting security standards and guidelines.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
