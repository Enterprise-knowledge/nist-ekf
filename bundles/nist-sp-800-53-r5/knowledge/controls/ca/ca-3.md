---
type: control
title: CA-3 - Information Exchange
description: SP 800-53 control CA-3.
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
- ca
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ca.md
  relation: part_of
  description: CA-3 - Information Exchange is part of its parent SP 800-53 structure.
- name: CA-3.1 - Unclassified National Security System Connections
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-3.1.md
  relation: has_enhancement
  description: CA-3 has enhancement CA-3.1.
- name: CA-3.2 - Classified National Security System Connections
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-3.2.md
  relation: has_enhancement
  description: CA-3 has enhancement CA-3.2.
- name: CA-3.3 - Unclassified Non-national Security System Connections
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-3.3.md
  relation: has_enhancement
  description: CA-3 has enhancement CA-3.3.
- name: CA-3.4 - Connections to Public Networks
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-3.4.md
  relation: has_enhancement
  description: CA-3 has enhancement CA-3.4.
- name: CA-3.5 - Restrictions on External System Connections
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-3.5.md
  relation: has_enhancement
  description: CA-3 has enhancement CA-3.5.
- name: CA-3.6 - Transfer Authorizations
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-3.6.md
  relation: has_enhancement
  description: CA-3 has enhancement CA-3.6.
- name: CA-3.7 - Transitive Information Exchanges
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-3.7.md
  relation: has_enhancement
  description: CA-3 has enhancement CA-3.7.
nist_id: CA-3
sort_id: ca-03
implementation_level: organization
parameter_ids:
- ca-03_odp.01
- ca-03_odp.02
- ca-03_odp.03
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#628d22a1-6a11-4784-bc59-5cd9497b5445'
- '#c3a76872-e160-4267-99e8-6952de967d04'
- '#ac-4'
- '#ac-20'
- '#au-16'
- '#ca-6'
- '#ia-3'
- '#ir-4'
- '#pl-2'
- '#pt-7'
- '#ra-3'
- '#sa-9'
- '#sc-7'
- '#si-12'
---

# Summary

SP 800-53 control CA-3.

# Statement

No statement text was present in the OSCAL record.

# Guidance

System information exchange requirements apply to information exchanges between two or more systems. System information exchanges include connections via leased lines or virtual private networks, connections to internet service providers, database sharing or exchanges of database transaction information, connections and exchanges with cloud services, exchanges via web-based services, or exchanges of files via file transfer protocols, network protocols (e.g., IPv4, IPv6), email, or other organization-to-organization communications. Organizations consider the risk related to new or increased threats that may be introduced when systems exchange information with other systems that may have different security and privacy requirements and controls. This includes systems within the same organization and systems that are external to the organization. A joint authorization of the systems exchanging information, as described in [CA-6(1)](#ca-6.1) or [CA-6(2)](#ca-6.2) , may help to communicate and reduce risk.

Authorizing officials determine the risk associated with system information exchange and the controls needed for appropriate risk mitigation. The types of agreements selected are based on factors such as the impact level of the information being exchanged, the relationship between the organizations exchanging information (e.g., government to government, government to business, business to business, government or business to service provider, government or business to individual), or the level of access to the organizational system by users of the other system. If systems that exchange information have the same authorizing official, organizations need not develop agreements. Instead, the interface characteristics between the systems (e.g., how the information is being exchanged. how the information is protected) are described in the respective security and privacy plans. If the systems that exchange information have different authorizing officials within the same organization, the organizations can develop agreements or provide the same information that would be provided in the appropriate agreement type from [CA-3a](#ca-3_smt.a) in the respective security and privacy plans for the systems. Organizations may incorporate agreement information into formal contracts, especially for information exchanges established between federal agencies and nonfederal organizations (including service providers, contractors, system developers, and system integrators). Risk considerations include systems that share the same networks.

# Parameters

- `ca-03_odp.01`
- `ca-03_odp.02`
- `ca-03_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
