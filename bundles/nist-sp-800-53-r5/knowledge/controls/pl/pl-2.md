---
type: control
title: PL-2 - System Security and Privacy Plans
description: SP 800-53 control PL-2.
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
- pl
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/pl.md
  relation: part_of
  description: PL-2 - System Security and Privacy Plans is part of its parent SP 800-53 structure.
- name: PL-2.1 - Concept of Operations
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pl/pl-2.1.md
  relation: has_enhancement
  description: PL-2 has enhancement PL-2.1.
- name: PL-2.2 - Functional Architecture
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pl/pl-2.2.md
  relation: has_enhancement
  description: PL-2 has enhancement PL-2.2.
- name: PL-2.3 - Plan and Coordinate with Other Organizational Entities
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pl/pl-2.3.md
  relation: has_enhancement
  description: PL-2 has enhancement PL-2.3.
nist_id: PL-2
sort_id: pl-02
implementation_level: organization
parameter_ids:
- pl-02_odp.01
- pl-02_odp.02
- pl-02_odp.03
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#30eb758a-2707-4bca-90ad-949a74d4eb16'
- '#482e4c99-9dc4-41ad-bba8-0f3f0032c1f8'
- '#e3cc0520-a366-4fc9-abc2-5272db7e3564'
- '#61ccf0f4-d3e7-42db-9796-ce6cb1c85989'
- '#ac-2'
- '#ac-6'
- '#ac-14'
- '#ac-17'
- '#ac-20'
- '#ca-2'
- '#ca-3'
- '#ca-7'
- '#cm-9'
- '#cm-13'
- '#cp-2'
- '#cp-4'
- '#ir-4'
- '#ir-8'
- '#ma-4'
- '#ma-5'
- '#mp-4'
- '#mp-5'
- '#pl-7'
- '#pl-8'
- '#pl-10'
- '#pl-11'
- '#pm-1'
- '#pm-7'
- '#pm-8'
- '#pm-9'
- '#pm-10'
- '#pm-11'
- '#ra-3'
- '#ra-8'
- '#ra-9'
- '#sa-5'
- '#sa-17'
- '#sa-22'
- '#si-12'
- '#sr-2'
- '#sr-4'
---

# Summary

SP 800-53 control PL-2.

# Statement

No statement text was present in the OSCAL record.

# Guidance

System security and privacy plans are scoped to the system and system components within the defined authorization boundary and contain an overview of the security and privacy requirements for the system and the controls selected to satisfy the requirements. The plans describe the intended application of each selected control in the context of the system with a sufficient level of detail to correctly implement the control and to subsequently assess the effectiveness of the control. The control documentation describes how system-specific and hybrid controls are implemented and the plans and expectations regarding the functionality of the system. System security and privacy plans can also be used in the design and development of systems in support of life cycle-based security and privacy engineering processes. System security and privacy plans are living documents that are updated and adapted throughout the system development life cycle (e.g., during capability determination, analysis of alternatives, requests for proposal, and design reviews). [Section 2.1](#c3397cc9-83c6-4459-adb2-836739dc1b94) describes the different types of requirements that are relevant to organizations during the system development life cycle and the relationship between requirements and controls.

Organizations may develop a single, integrated security and privacy plan or maintain separate plans. Security and privacy plans relate security and privacy requirements to a set of controls and control enhancements. The plans describe how the controls and control enhancements meet the security and privacy requirements but do not provide detailed, technical descriptions of the design or implementation of the controls and control enhancements. Security and privacy plans contain sufficient information (including specifications of control parameter values for selection and assignment operations explicitly or by reference) to enable a design and implementation that is unambiguously compliant with the intent of the plans and subsequent determinations of risk to organizational operations and assets, individuals, other organizations, and the Nation if the plan is implemented.

Security and privacy plans need not be single documents. The plans can be a collection of various documents, including documents that already exist. Effective security and privacy plans make extensive use of references to policies, procedures, and additional documents, including design and implementation specifications where more detailed information can be obtained. The use of references helps reduce the documentation associated with security and privacy programs and maintains the security- and privacy-related information in other established management and operational areas, including enterprise architecture, system development life cycle, systems engineering, and acquisition. Security and privacy plans need not contain detailed contingency plan or incident response plan information but can instead provide—explicitly or by reference—sufficient information to define what needs to be accomplished by those plans.

Security- and privacy-related activities that may require coordination and planning with other individuals or groups within the organization include assessments, audits, inspections, hardware and software maintenance, acquisition and supply chain risk management, patch management, and contingency plan testing. Planning and coordination include emergency and nonemergency (i.e., planned or non-urgent unplanned) situations. The process defined by organizations to plan and coordinate security- and privacy-related activities can also be included in other documents, as appropriate.

# Parameters

- `pl-02_odp.01`
- `pl-02_odp.02`
- `pl-02_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
