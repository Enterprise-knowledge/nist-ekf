---
type: control
title: MA-4 - Nonlocal Maintenance
description: SP 800-53 control MA-4.
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
- ma
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ma.md
  relation: part_of
  description: MA-4 - Nonlocal Maintenance is part of its parent SP 800-53 structure.
- name: MA-4.1 - Logging and Review
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-4.1.md
  relation: has_enhancement
  description: MA-4 has enhancement MA-4.1.
- name: MA-4.2 - Document Nonlocal Maintenance
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-4.2.md
  relation: has_enhancement
  description: MA-4 has enhancement MA-4.2.
- name: MA-4.3 - Comparable Security and Sanitization
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-4.3.md
  relation: has_enhancement
  description: MA-4 has enhancement MA-4.3.
- name: MA-4.4 - Authentication and Separation of Maintenance Sessions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-4.4.md
  relation: has_enhancement
  description: MA-4 has enhancement MA-4.4.
- name: MA-4.5 - Approvals and Notifications
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-4.5.md
  relation: has_enhancement
  description: MA-4 has enhancement MA-4.5.
- name: MA-4.6 - Cryptographic Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-4.6.md
  relation: has_enhancement
  description: MA-4 has enhancement MA-4.6.
- name: MA-4.7 - Disconnect Verification
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-4.7.md
  relation: has_enhancement
  description: MA-4 has enhancement MA-4.7.
nist_id: MA-4
sort_id: ma-04
implementation_level: organization
parameter_ids: []
reference_links:
- '#678e3d6c-150b-4393-aec5-6e3481eb1e00'
- '#736d6310-e403-4b57-a79d-9967970c66d7'
- '#7ba1d91c-3934-4d5a-8532-b32f864ad34c'
- '#737513fa-6758-403f-831d-5ddab5e23cb3'
- '#a5b1d18d-e670-4586-9e6d-4a88b7ba3df6'
- '#ac-2'
- '#ac-3'
- '#ac-6'
- '#ac-17'
- '#au-2'
- '#au-3'
- '#ia-2'
- '#ia-4'
- '#ia-5'
- '#ia-8'
- '#ma-2'
- '#ma-5'
- '#pl-2'
- '#sc-7'
- '#sc-10'
---

# Summary

SP 800-53 control MA-4.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Nonlocal maintenance and diagnostic activities are conducted by individuals who communicate through either an external or internal network. Local maintenance and diagnostic activities are carried out by individuals who are physically present at the system location and not communicating across a network connection. Authentication techniques used to establish nonlocal maintenance and diagnostic sessions reflect the network access requirements in [IA-2](#ia-2) . Strong authentication requires authenticators that are resistant to replay attacks and employ multi-factor authentication. Strong authenticators include PKI where certificates are stored on a token protected by a password, passphrase, or biometric. Enforcing requirements in [MA-4](#ma-4) is accomplished, in part, by other controls. [SP 800-63B](#e59c5a7c-8b1f-49ca-8de0-6ee0882180ce) provides additional guidance on strong authentication and authenticators.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
