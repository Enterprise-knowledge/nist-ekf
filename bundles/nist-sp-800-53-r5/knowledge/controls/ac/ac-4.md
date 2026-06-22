---
type: control
title: AC-4 - Information Flow Enforcement
description: 'Enforce approved authorizations for controlling the flow of information within the system and between
  connected systems based on {{ insert: param, ac-04_odp }}.'
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
- ac
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ac.md
  relation: part_of
  description: AC-4 - Information Flow Enforcement is part of its parent SP 800-53 structure.
- name: AC-4.1 - Object Security and Privacy Attributes
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.1.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.1.
- name: AC-4.2 - Processing Domains
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.2.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.2.
- name: AC-4.3 - Dynamic Information Flow Control
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.3.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.3.
- name: AC-4.4 - Flow Control of Encrypted Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.4.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.4.
- name: AC-4.5 - Embedded Data Types
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.5.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.5.
- name: AC-4.6 - Metadata
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.6.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.6.
- name: AC-4.7 - One-way Flow Mechanisms
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.7.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.7.
- name: AC-4.8 - Security and Privacy Policy Filters
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.8.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.8.
- name: AC-4.9 - Human Reviews
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.9.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.9.
- name: AC-4.10 - Enable and Disable Security or Privacy Policy Filters
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.10.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.10.
- name: AC-4.11 - Configuration of Security or Privacy Policy Filters
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.11.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.11.
- name: AC-4.12 - Data Type Identifiers
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.12.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.12.
- name: AC-4.13 - Decomposition into Policy-relevant Subcomponents
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.13.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.13.
- name: AC-4.14 - Security or Privacy Policy Filter Constraints
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.14.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.14.
- name: AC-4.15 - Detection of Unsanctioned Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.15.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.15.
- name: AC-4.16 - Information Transfers on Interconnected Systems
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.16.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.16.
- name: AC-4.17 - Domain Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.17.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.17.
- name: AC-4.18 - Security Attribute Binding
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.18.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.18.
- name: AC-4.19 - Validation of Metadata
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.19.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.19.
- name: AC-4.20 - Approved Solutions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.20.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.20.
- name: AC-4.21 - Physical or Logical Separation of Information Flows
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.21.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.21.
- name: AC-4.22 - Access Only
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.22.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.22.
- name: AC-4.23 - Modify Non-releasable Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.23.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.23.
- name: AC-4.24 - Internal Normalized Format
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.24.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.24.
- name: AC-4.25 - Data Sanitization
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.25.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.25.
- name: AC-4.26 - Audit Filtering Actions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.26.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.26.
- name: AC-4.27 - Redundant/Independent Filtering Mechanisms
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.27.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.27.
- name: AC-4.28 - Linear Filter Pipelines
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.28.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.28.
- name: AC-4.29 - Filter Orchestration Engines
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.29.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.29.
- name: AC-4.30 - Filter Mechanisms Using Multiple Processes
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.30.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.30.
- name: AC-4.31 - Failed Content Transfer Prevention
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.31.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.31.
- name: AC-4.32 - Process Requirements for Information Transfer
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ac/ac-4.32.md
  relation: has_enhancement
  description: AC-4 has enhancement AC-4.32.
nist_id: AC-4
sort_id: ac-04
implementation_level: system
parameter_ids:
- ac-04_odp
reference_links:
- '#e3cc0520-a366-4fc9-abc2-5272db7e3564'
- '#2956e175-f674-43f4-b1b9-e074ad9fc39c'
- '#388a3aa2-5d85-4bad-b8a3-77db80d63c4f'
- '#a2590922-82f3-4277-83c0-ca5bee06dba4'
- '#ac-3'
- '#ac-6'
- '#ac-16'
- '#ac-17'
- '#ac-19'
- '#ac-21'
- '#au-10'
- '#ca-3'
- '#ca-9'
- '#cm-7'
- '#pl-9'
- '#pm-24'
- '#sa-17'
- '#sc-4'
- '#sc-7'
- '#sc-16'
- '#sc-31'
---

# Summary

Enforce approved authorizations for controlling the flow of information within the system and between connected systems based on {{ insert: param, ac-04_odp }}.

# Statement

Enforce approved authorizations for controlling the flow of information within the system and between connected systems based on {{ insert: param, ac-04_odp }}.

# Guidance

Information flow control regulates where information can travel within a system and between systems (in contrast to who is allowed to access the information) and without regard to subsequent accesses to that information. Flow control restrictions include blocking external traffic that claims to be from within the organization, keeping export-controlled information from being transmitted in the clear to the Internet, restricting web requests that are not from the internal web proxy server, and limiting information transfers between organizations based on data structures and content. Transferring information between organizations may require an agreement specifying how the information flow is enforced (see [CA-3](#ca-3) ). Transferring information between systems in different security or privacy domains with different security or privacy policies introduces the risk that such transfers violate one or more domain security or privacy policies. In such situations, information owners/stewards provide guidance at designated policy enforcement points between connected systems. Organizations consider mandating specific architectural solutions to enforce specific security and privacy policies. Enforcement includes prohibiting information transfers between connected systems (i.e., allowing access only), verifying write permissions before accepting information from another security or privacy domain or connected system, employing hardware mechanisms to enforce one-way information flows, and implementing trustworthy regrading mechanisms to reassign security or privacy attributes and labels.

Organizations commonly employ information flow control policies and enforcement mechanisms to control the flow of information between designated sources and destinations within systems and between connected systems. Flow control is based on the characteristics of the information and/or the information path. Enforcement occurs, for example, in boundary protection devices that employ rule sets or establish configuration settings that restrict system services, provide a packet-filtering capability based on header information, or provide a message-filtering capability based on message content. Organizations also consider the trustworthiness of filtering and/or inspection mechanisms (i.e., hardware, firmware, and software components) that are critical to information flow enforcement. Control enhancements 3 through 32 primarily address cross-domain solution needs that focus on more advanced filtering techniques, in-depth analysis, and stronger flow enforcement mechanisms implemented in cross-domain products, such as high-assurance guards. Such capabilities are generally not available in commercial off-the-shelf products. Information flow enforcement also applies to control plane traffic (e.g., routing and DNS).

# Parameters

- `ac-04_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
