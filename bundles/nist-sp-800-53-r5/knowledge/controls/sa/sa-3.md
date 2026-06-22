---
type: control
title: SA-3 - System Development Life Cycle
description: SP 800-53 control SA-3.
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/sa.md
  relation: part_of
  description: SA-3 - System Development Life Cycle is part of its parent SP 800-53 structure.
- name: SA-3.1 - Manage Preproduction Environment
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-3.1.md
  relation: has_enhancement
  description: SA-3 has enhancement SA-3.1.
- name: SA-3.2 - Use of Live or Operational Data
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-3.2.md
  relation: has_enhancement
  description: SA-3 has enhancement SA-3.2.
- name: SA-3.3 - Technology Refresh
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-3.3.md
  relation: has_enhancement
  description: SA-3 has enhancement SA-3.3.
nist_id: SA-3
sort_id: sa-03
implementation_level: organization
parameter_ids:
- sa-03_odp
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#08b07465-dbdc-48d6-8a0b-37279602ac16'
- '#482e4c99-9dc4-41ad-bba8-0f3f0032c1f8'
- '#e3cc0520-a366-4fc9-abc2-5272db7e3564'
- '#7dbd6d9f-29d6-4d1d-9766-f2d77ff3c849'
- '#f26af0d0-6d72-4a9d-8ecd-01bc21fd4f0e'
- '#at-3'
- '#pl-8'
- '#pm-7'
- '#sa-4'
- '#sa-5'
- '#sa-8'
- '#sa-11'
- '#sa-15'
- '#sa-17'
- '#sa-22'
- '#sr-3'
- '#sr-4'
- '#sr-5'
- '#sr-9'
---

# Summary

SP 800-53 control SA-3.

# Statement

No statement text was present in the OSCAL record.

# Guidance

A system development life cycle process provides the foundation for the successful development, implementation, and operation of organizational systems. The integration of security and privacy considerations early in the system development life cycle is a foundational principle of systems security engineering and privacy engineering. To apply the required controls within the system development life cycle requires a basic understanding of information security and privacy, threats, vulnerabilities, adverse impacts, and risk to critical mission and business functions. The security engineering principles in [SA-8](#sa-8) help individuals properly design, code, and test systems and system components. Organizations include qualified personnel (e.g., senior agency information security officers, senior agency officials for privacy, security and privacy architects, and security and privacy engineers) in system development life cycle processes to ensure that established security and privacy requirements are incorporated into organizational systems. Role-based security and privacy training programs can ensure that individuals with key security and privacy roles and responsibilities have the experience, skills, and expertise to conduct assigned system development life cycle activities.

The effective integration of security and privacy requirements into enterprise architecture also helps to ensure that important security and privacy considerations are addressed throughout the system life cycle and that those considerations are directly related to organizational mission and business processes. This process also facilitates the integration of the information security and privacy architectures into the enterprise architecture, consistent with the risk management strategy of the organization. Because the system development life cycle involves multiple organizations, (e.g., external suppliers, developers, integrators, service providers), acquisition and supply chain risk management functions and controls play significant roles in the effective management of the system during the life cycle.

# Parameters

- `sa-03_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
