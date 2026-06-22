---
type: control
title: SA-8 - Security and Privacy Engineering Principles
description: 'Apply the following systems security and privacy engineering principles in the specification, design,
  development, implementation, and modification of the system and system components: {{ insert: param, sa-8_prm_1
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
  description: SA-8 - Security and Privacy Engineering Principles is part of its parent SP 800-53 structure.
- name: SA-8.1 - Clear Abstractions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.1.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.1.
- name: SA-8.2 - Least Common Mechanism
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.2.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.2.
- name: SA-8.3 - Modularity and Layering
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.3.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.3.
- name: SA-8.4 - Partially Ordered Dependencies
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.4.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.4.
- name: SA-8.5 - Efficiently Mediated Access
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.5.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.5.
- name: SA-8.6 - Minimized Sharing
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.6.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.6.
- name: SA-8.7 - Reduced Complexity
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.7.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.7.
- name: SA-8.8 - Secure Evolvability
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.8.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.8.
- name: SA-8.9 - Trusted Components
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.9.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.9.
- name: SA-8.10 - Hierarchical Trust
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.10.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.10.
- name: SA-8.11 - Inverse Modification Threshold
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.11.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.11.
- name: SA-8.12 - Hierarchical Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.12.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.12.
- name: SA-8.13 - Minimized Security Elements
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.13.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.13.
- name: SA-8.14 - Least Privilege
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.14.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.14.
- name: SA-8.15 - Predicate Permission
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.15.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.15.
- name: SA-8.16 - Self-reliant Trustworthiness
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.16.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.16.
- name: SA-8.17 - Secure Distributed Composition
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.17.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.17.
- name: SA-8.18 - Trusted Communications Channels
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.18.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.18.
- name: SA-8.19 - Continuous Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.19.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.19.
- name: SA-8.20 - Secure Metadata Management
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.20.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.20.
- name: SA-8.21 - Self-analysis
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.21.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.21.
- name: SA-8.22 - Accountability and Traceability
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.22.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.22.
- name: SA-8.23 - Secure Defaults
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.23.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.23.
- name: SA-8.24 - Secure Failure and Recovery
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.24.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.24.
- name: SA-8.25 - Economic Security
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.25.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.25.
- name: SA-8.26 - Performance Security
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.26.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.26.
- name: SA-8.27 - Human Factored Security
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.27.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.27.
- name: SA-8.28 - Acceptable Security
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.28.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.28.
- name: SA-8.29 - Repeatable and Documented Procedures
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.29.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.29.
- name: SA-8.30 - Procedural Rigor
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.30.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.30.
- name: SA-8.31 - Secure System Modification
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.31.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.31.
- name: SA-8.32 - Sufficient Documentation
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.32.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.32.
- name: SA-8.33 - Minimization
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-8.33.md
  relation: has_enhancement
  description: SA-8 has enhancement SA-8.33.
nist_id: SA-8
sort_id: sa-08
implementation_level: organization
parameter_ids:
- sa-8_prm_1
- sa-08_odp.01
- sa-08_odp.02
reference_links:
- '#18e71fec-c6fd-475a-925a-5d8495cf8455'
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#628d22a1-6a11-4784-bc59-5cd9497b5445'
- '#599fb53d-5041-444e-a7fe-640d6d30ad05'
- '#482e4c99-9dc4-41ad-bba8-0f3f0032c1f8'
- '#a21aef46-7330-48a0-b2e1-c5bb8b2dd11d'
- '#e72fde0b-6fc2-497e-a9db-d8fce5a11b8a'
- '#9be5d661-421f-41ad-854e-86f98b811891'
- '#e3cc0520-a366-4fc9-abc2-5272db7e3564'
- '#98d415ca-7281-4064-9931-0c366637e324'
- '#61ccf0f4-d3e7-42db-9796-ce6cb1c85989'
- '#pl-8'
- '#pm-7'
- '#ra-2'
- '#ra-3'
- '#ra-9'
- '#sa-3'
- '#sa-4'
- '#sa-15'
- '#sa-17'
- '#sa-20'
- '#sc-2'
- '#sc-3'
- '#sc-32'
- '#sc-39'
- '#sr-2'
- '#sr-3'
- '#sr-4'
- '#sr-5'
---

# Summary

Apply the following systems security and privacy engineering principles in the specification, design, development, implementation, and modification of the system and system components: {{ insert: param, sa-8_prm_1 }}.

# Statement

Apply the following systems security and privacy engineering principles in the specification, design, development, implementation, and modification of the system and system components: {{ insert: param, sa-8_prm_1 }}.

# Guidance

Systems security and privacy engineering principles are closely related to and implemented throughout the system development life cycle (see [SA-3](#sa-3) ). Organizations can apply systems security and privacy engineering principles to new systems under development or to systems undergoing upgrades. For existing systems, organizations apply systems security and privacy engineering principles to system upgrades and modifications to the extent feasible, given the current state of hardware, software, and firmware components within those systems.

The application of systems security and privacy engineering principles helps organizations develop trustworthy, secure, and resilient systems and reduces the susceptibility to disruptions, hazards, threats, and the creation of privacy problems for individuals. Examples of system security engineering principles include: developing layered protections; establishing security and privacy policies, architecture, and controls as the foundation for design and development; incorporating security and privacy requirements into the system development life cycle; delineating physical and logical security boundaries; ensuring that developers are trained on how to build secure software; tailoring controls to meet organizational needs; and performing threat modeling to identify use cases, threat agents, attack vectors and patterns, design patterns, and compensating controls needed to mitigate risk.

Organizations that apply systems security and privacy engineering concepts and principles can facilitate the development of trustworthy, secure systems, system components, and system services; reduce risk to acceptable levels; and make informed risk management decisions. System security engineering principles can also be used to protect against certain supply chain risks, including incorporating tamper-resistant hardware into a design.

# Parameters

- `sa-8_prm_1`
- `sa-08_odp.01`
- `sa-08_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
