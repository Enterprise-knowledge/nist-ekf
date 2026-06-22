---
type: control
title: CA-2 - Control Assessments
description: SP 800-53 control CA-2.
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
  description: CA-2 - Control Assessments is part of its parent SP 800-53 structure.
- name: CA-2.1 - Independent Assessors
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-2.1.md
  relation: has_enhancement
  description: CA-2 has enhancement CA-2.1.
- name: CA-2.2 - Specialized Assessments
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-2.2.md
  relation: has_enhancement
  description: CA-2 has enhancement CA-2.2.
- name: CA-2.3 - Leveraging Results from External Organizations
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-2.3.md
  relation: has_enhancement
  description: CA-2 has enhancement CA-2.3.
nist_id: CA-2
sort_id: ca-02
implementation_level: organization
parameter_ids:
- ca-02_odp.01
- ca-02_odp.02
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#628d22a1-6a11-4784-bc59-5cd9497b5445'
- '#30eb758a-2707-4bca-90ad-949a74d4eb16'
- '#482e4c99-9dc4-41ad-bba8-0f3f0032c1f8'
- '#cec037f3-8aba-4c97-84b4-4082f9e515d2'
- '#a21aef46-7330-48a0-b2e1-c5bb8b2dd11d'
- '#122177fa-c4ed-485d-8345-3082c0fb9a06'
- '#067223d8-1ec7-45c5-b21b-c848da6de8fb'
- '#bbac9fc2-df5b-4f2d-bf99-90d0ade45349'
- '#98d415ca-7281-4064-9931-0c366637e324'
- '#ac-20'
- '#ca-5'
- '#ca-6'
- '#ca-7'
- '#pm-9'
- '#ra-5'
- '#ra-10'
- '#sa-11'
- '#sc-38'
- '#si-3'
- '#si-12'
- '#sr-2'
- '#sr-3'
---

# Summary

SP 800-53 control CA-2.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Organizations ensure that control assessors possess the required skills and technical expertise to develop effective assessment plans and to conduct assessments of system-specific, hybrid, common, and program management controls, as appropriate. The required skills include general knowledge of risk management concepts and approaches as well as comprehensive knowledge of and experience with the hardware, software, and firmware system components implemented.

Organizations assess controls in systems and the environments in which those systems operate as part of initial and ongoing authorizations, continuous monitoring, FISMA annual assessments, system design and development, systems security engineering, privacy engineering, and the system development life cycle. Assessments help to ensure that organizations meet information security and privacy requirements, identify weaknesses and deficiencies in the system design and development process, provide essential information needed to make risk-based decisions as part of authorization processes, and comply with vulnerability mitigation procedures. Organizations conduct assessments on the implemented controls as documented in security and privacy plans. Assessments can also be conducted throughout the system development life cycle as part of systems engineering and systems security engineering processes. The design for controls can be assessed as RFPs are developed, responses assessed, and design reviews conducted. If a design to implement controls and subsequent implementation in accordance with the design are assessed during development, the final control testing can be a simple confirmation utilizing previously completed control assessment and aggregating the outcomes.

Organizations may develop a single, consolidated security and privacy assessment plan for the system or maintain separate plans. A consolidated assessment plan clearly delineates the roles and responsibilities for control assessment. If multiple organizations participate in assessing a system, a coordinated approach can reduce redundancies and associated costs.

Organizations can use other types of assessment activities, such as vulnerability scanning and system monitoring, to maintain the security and privacy posture of systems during the system life cycle. Assessment reports document assessment results in sufficient detail, as deemed necessary by organizations, to determine the accuracy and completeness of the reports and whether the controls are implemented correctly, operating as intended, and producing the desired outcome with respect to meeting requirements. Assessment results are provided to the individuals or roles appropriate for the types of assessments being conducted. For example, assessments conducted in support of authorization decisions are provided to authorizing officials, senior agency officials for privacy, senior agency information security officers, and authorizing official designated representatives.

To satisfy annual assessment requirements, organizations can use assessment results from the following sources: initial or ongoing system authorizations, continuous monitoring, systems engineering processes, or system development life cycle activities. Organizations ensure that assessment results are current, relevant to the determination of control effectiveness, and obtained with the appropriate level of assessor independence. Existing control assessment results can be reused to the extent that the results are still valid and can also be supplemented with additional assessments as needed. After the initial authorizations, organizations assess controls during continuous monitoring. Organizations also establish the frequency for ongoing assessments in accordance with organizational continuous monitoring strategies. External audits, including audits by external entities such as regulatory agencies, are outside of the scope of [CA-2](#ca-2).

# Parameters

- `ca-02_odp.01`
- `ca-02_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
