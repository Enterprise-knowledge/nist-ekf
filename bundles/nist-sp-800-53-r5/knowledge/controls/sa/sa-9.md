---
type: control
title: SA-9 - External System Services
description: SP 800-53 control SA-9.
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
  description: SA-9 - External System Services is part of its parent SP 800-53 structure.
- name: SA-9.1 - Risk Assessments and Organizational Approvals
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-9.1.md
  relation: has_enhancement
  description: SA-9 has enhancement SA-9.1.
- name: SA-9.2 - Identification of Functions, Ports, Protocols, and Services
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-9.2.md
  relation: has_enhancement
  description: SA-9 has enhancement SA-9.2.
- name: SA-9.3 - Establish and Maintain Trust Relationship with Providers
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-9.3.md
  relation: has_enhancement
  description: SA-9 has enhancement SA-9.3.
- name: SA-9.4 - Consistent Interests of Consumers and Providers
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-9.4.md
  relation: has_enhancement
  description: SA-9 has enhancement SA-9.4.
- name: SA-9.5 - Processing, Storage, and Service Location
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-9.5.md
  relation: has_enhancement
  description: SA-9 has enhancement SA-9.5.
- name: SA-9.6 - Organization-controlled Cryptographic Keys
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-9.6.md
  relation: has_enhancement
  description: SA-9 has enhancement SA-9.6.
- name: SA-9.7 - Organization-controlled Integrity Checking
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-9.7.md
  relation: has_enhancement
  description: SA-9 has enhancement SA-9.7.
- name: SA-9.8 - Processing and Storage Location — U.S. Jurisdiction
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-9.8.md
  relation: has_enhancement
  description: SA-9 has enhancement SA-9.8.
nist_id: SA-9
sort_id: sa-09
implementation_level: organization
parameter_ids:
- sa-09_odp.01
- sa-09_odp.02
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#77faf0bc-c394-44ad-9154-bbac3b79c8ad'
- '#e3cc0520-a366-4fc9-abc2-5272db7e3564'
- '#e8e84963-14fc-4c3a-be05-b412a5d37cd2'
- '#7dbd6d9f-29d6-4d1d-9766-f2d77ff3c849'
- '#ac-20'
- '#ca-3'
- '#cp-2'
- '#ir-4'
- '#ir-7'
- '#pl-10'
- '#pl-11'
- '#ps-7'
- '#sa-2'
- '#sa-4'
- '#sr-3'
- '#sr-5'
---

# Summary

SP 800-53 control SA-9.

# Statement

No statement text was present in the OSCAL record.

# Guidance

External system services are provided by an external provider, and the organization has no direct control over the implementation of the required controls or the assessment of control effectiveness. Organizations establish relationships with external service providers in a variety of ways, including through business partnerships, contracts, interagency agreements, lines of business arrangements, licensing agreements, joint ventures, and supply chain exchanges. The responsibility for managing risks from the use of external system services remains with authorizing officials. For services external to organizations, a chain of trust requires that organizations establish and retain a certain level of confidence that each provider in the consumer-provider relationship provides adequate protection for the services rendered. The extent and nature of this chain of trust vary based on relationships between organizations and the external providers. Organizations document the basis for the trust relationships so that the relationships can be monitored. External system services documentation includes government, service providers, end user security roles and responsibilities, and service-level agreements. Service-level agreements define the expectations of performance for implemented controls, describe measurable outcomes, and identify remedies and response requirements for identified instances of noncompliance.

# Parameters

- `sa-09_odp.01`
- `sa-09_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
