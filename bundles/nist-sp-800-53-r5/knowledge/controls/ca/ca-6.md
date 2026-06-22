---
type: control
title: CA-6 - Authorization
description: SP 800-53 control CA-6.
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
  description: CA-6 - Authorization is part of its parent SP 800-53 structure.
- name: CA-6.1 - Joint Authorization — Intra-organization
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-6.1.md
  relation: has_enhancement
  description: CA-6 has enhancement CA-6.1.
- name: CA-6.2 - Joint Authorization — Inter-organization
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-6.2.md
  relation: has_enhancement
  description: CA-6 has enhancement CA-6.2.
nist_id: CA-6
sort_id: ca-06
implementation_level: organization
parameter_ids:
- ca-06_odp
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#482e4c99-9dc4-41ad-bba8-0f3f0032c1f8'
- '#067223d8-1ec7-45c5-b21b-c848da6de8fb'
- '#ca-2'
- '#ca-3'
- '#ca-7'
- '#pm-9'
- '#pm-10'
- '#ra-3'
- '#sa-10'
- '#si-12'
---

# Summary

SP 800-53 control CA-6.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Authorizations are official management decisions by senior officials to authorize operation of systems, authorize the use of common controls for inheritance by organizational systems, and explicitly accept the risk to organizational operations and assets, individuals, other organizations, and the Nation based on the implementation of agreed-upon controls. Authorizing officials provide budgetary oversight for organizational systems and common controls or assume responsibility for the mission and business functions supported by those systems or common controls. The authorization process is a federal responsibility, and therefore, authorizing officials must be federal employees. Authorizing officials are both responsible and accountable for security and privacy risks associated with the operation and use of organizational systems. Nonfederal organizations may have similar processes to authorize systems and senior officials that assume the authorization role and associated responsibilities.

Authorizing officials issue ongoing authorizations of systems based on evidence produced from implemented continuous monitoring programs. Robust continuous monitoring programs reduce the need for separate reauthorization processes. Through the employment of comprehensive continuous monitoring processes, the information contained in authorization packages (i.e., security and privacy plans, assessment reports, and plans of action and milestones) is updated on an ongoing basis. This provides authorizing officials, common control providers, and system owners with an up-to-date status of the security and privacy posture of their systems, controls, and operating environments. To reduce the cost of reauthorization, authorizing officials can leverage the results of continuous monitoring processes to the maximum extent possible as the basis for rendering reauthorization decisions.

# Parameters

- `ca-06_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
