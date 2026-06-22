---
type: control_family
title: CA - Assessment, Authorization, and Monitoring
description: SP 800-53 control family for Assessment, Authorization, and Monitoring.
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control-family
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
- name: The Controls
  path: /bundles/nist-sp-800-53-r5/knowledge/sections/controls.md
  relation: part_of
  description: This family is part of the controls section.
- name: CA-1 - Policy and Procedures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ca/ca-1.md
  relation: contains
  description: The family contains control CA-1.
- name: CA-2 - Control Assessments
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ca/ca-2.md
  relation: contains
  description: The family contains control CA-2.
- name: CA-3 - Information Exchange
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ca/ca-3.md
  relation: contains
  description: The family contains control CA-3.
- name: CA-4 - Security Certification
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ca/ca-4.md
  relation: contains
  description: The family contains control CA-4.
- name: CA-5 - Plan of Action and Milestones
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ca/ca-5.md
  relation: contains
  description: The family contains control CA-5.
- name: CA-6 - Authorization
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ca/ca-6.md
  relation: contains
  description: The family contains control CA-6.
- name: CA-7 - Continuous Monitoring
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ca/ca-7.md
  relation: contains
  description: The family contains control CA-7.
- name: CA-8 - Penetration Testing
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ca/ca-8.md
  relation: contains
  description: The family contains control CA-8.
- name: CA-9 - Internal System Connections
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ca/ca-9.md
  relation: contains
  description: The family contains control CA-9.
nist_id: CA
base_control_count: 9
control_enhancement_count: 23
---

# Summary

The Assessment, Authorization, and Monitoring family contains 9 base controls and 23 control enhancements in the NIST OSCAL catalog.

# Controls

- [CA-1 - Policy and Procedures](../controls/ca/ca-1.md) - SP 800-53 control CA-1.
- [CA-2 - Control Assessments](../controls/ca/ca-2.md) - SP 800-53 control CA-2.
- [CA-3 - Information Exchange](../controls/ca/ca-3.md) - SP 800-53 control CA-3.
- [CA-4 - Security Certification](../controls/ca/ca-4.md) - SP 800-53 control CA-4.
- [CA-5 - Plan of Action and Milestones](../controls/ca/ca-5.md) - SP 800-53 control CA-5.
- [CA-6 - Authorization](../controls/ca/ca-6.md) - SP 800-53 control CA-6.
- [CA-7 - Continuous Monitoring](../controls/ca/ca-7.md) - Develop a system-level continuous monitoring strategy and implement continuous monitoring in accordance with the organization-level continuous monitoring strategy that includes:
- [CA-8 - Penetration Testing](../controls/ca/ca-8.md) - Conduct penetration testing {{ insert: param, ca-08_odp.01 }} on {{ insert: param, ca-08_odp.02 }}.
- [CA-9 - Internal System Connections](../controls/ca/ca-9.md) - SP 800-53 control CA-9.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
