---
type: control_enhancement
title: AC-3.4 - Discretionary Access Control
description: 'Enforce {{ insert: param, ac-3.4_prm_1 }} over the set of covered subjects and objects specified in
  the policy, and where the policy specifies that a subject that has been granted access to information can do one
  or more'
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control-enhancement
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-3.md
  relation: part_of
  description: AC-3.4 - Discretionary Access Control is part of its parent SP 800-53 structure.
- name: AC-3 - Access Enforcement
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-3.md
  relation: enhances
  description: AC-3.4 enhances base control AC-3.
nist_id: AC-3.4
sort_id: ac-03.04
implementation_level: system
parameter_ids:
- ac-3.4_prm_1
- ac-03.04_odp.01
- ac-03.04_odp.02
reference_links:
- '#ac-3'
---

# Summary

Enforce {{ insert: param, ac-3.4_prm_1 }} over the set of covered subjects and objects specified in the policy, and where the policy specifies that a subject that has been granted access to information can do one or more

# Statement

Enforce {{ insert: param, ac-3.4_prm_1 }} over the set of covered subjects and objects specified in the policy, and where the policy specifies that a subject that has been granted access to information can do one or more of the following:

# Guidance

When discretionary access control policies are implemented, subjects are not constrained with regard to what actions they can take with information for which they have already been granted access. Thus, subjects that have been granted access to information are not prevented from passing the information to other subjects or objects (i.e., subjects have the discretion to pass). Discretionary access control can operate in conjunction with mandatory access control as described in [AC-3(3)](#ac-3.3) and [AC-3(15)](#ac-3.15) . A subject that is constrained in its operation by mandatory access control policies can still operate under the less rigorous constraints of discretionary access control. Therefore, while [AC-3(3)](#ac-3.3) imposes constraints that prevent a subject from passing information to another subject operating at a different impact or classification level, [AC-3(4)](#ac-3.4) permits the subject to pass the information to any subject at the same impact or classification level. The policy is bounded by the system. Once the information is passed outside of system control, additional means may be required to ensure that the constraints remain in effect. While traditional definitions of discretionary access control require identity-based access control, that limitation is not required for this particular use of discretionary access control.

# Parameters

- `ac-3.4_prm_1`
- `ac-03.04_odp.01`
- `ac-03.04_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
