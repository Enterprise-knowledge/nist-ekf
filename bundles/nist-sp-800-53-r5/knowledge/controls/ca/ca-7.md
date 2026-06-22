---
type: control
title: CA-7 - Continuous Monitoring
description: 'Develop a system-level continuous monitoring strategy and implement continuous monitoring in accordance
  with the organization-level continuous monitoring strategy that includes:'
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
  description: CA-7 - Continuous Monitoring is part of its parent SP 800-53 structure.
- name: CA-7.1 - Independent Assessment
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-7.1.md
  relation: has_enhancement
  description: CA-7 has enhancement CA-7.1.
- name: CA-7.2 - Types of Assessments
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-7.2.md
  relation: has_enhancement
  description: CA-7 has enhancement CA-7.2.
- name: CA-7.3 - Trend Analyses
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-7.3.md
  relation: has_enhancement
  description: CA-7 has enhancement CA-7.3.
- name: CA-7.4 - Risk Monitoring
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-7.4.md
  relation: has_enhancement
  description: CA-7 has enhancement CA-7.4.
- name: CA-7.5 - Consistency Analysis
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-7.5.md
  relation: has_enhancement
  description: CA-7 has enhancement CA-7.5.
- name: CA-7.6 - Automation Support for Monitoring
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-7.6.md
  relation: has_enhancement
  description: CA-7 has enhancement CA-7.6.
nist_id: CA-7
sort_id: ca-07
implementation_level: organization
parameter_ids:
- ca-7_prm_4
- ca-7_prm_5
- ca-07_odp.01
- ca-07_odp.02
- ca-07_odp.03
- ca-07_odp.04
- ca-07_odp.05
- ca-07_odp.06
- ca-07_odp.07
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#482e4c99-9dc4-41ad-bba8-0f3f0032c1f8'
- '#cec037f3-8aba-4c97-84b4-4082f9e515d2'
- '#a21aef46-7330-48a0-b2e1-c5bb8b2dd11d'
- '#122177fa-c4ed-485d-8345-3082c0fb9a06'
- '#067223d8-1ec7-45c5-b21b-c848da6de8fb'
- '#bbac9fc2-df5b-4f2d-bf99-90d0ade45349'
- '#98d415ca-7281-4064-9931-0c366637e324'
- '#ac-2'
- '#ac-6'
- '#ac-17'
- '#at-4'
- '#au-6'
- '#au-13'
- '#ca-2'
- '#ca-5'
- '#ca-6'
- '#cm-3'
- '#cm-4'
- '#cm-6'
- '#cm-11'
- '#ia-5'
- '#ir-5'
- '#ma-2'
- '#ma-3'
- '#ma-4'
- '#pe-3'
- '#pe-6'
- '#pe-14'
- '#pe-16'
- '#pe-20'
- '#pl-2'
- '#pm-4'
- '#pm-6'
- '#pm-9'
- '#pm-10'
- '#pm-12'
- '#pm-14'
- '#pm-23'
- '#pm-28'
- '#pm-31'
- '#ps-7'
- '#pt-7'
- '#ra-3'
- '#ra-5'
- '#ra-7'
- '#ra-10'
- '#sa-8'
- '#sa-9'
- '#sa-11'
- '#sc-5'
- '#sc-7'
- '#sc-18'
- '#sc-38'
- '#sc-43'
- '#si-3'
- '#si-4'
- '#si-12'
- '#sr-6'
---

# Summary

Develop a system-level continuous monitoring strategy and implement continuous monitoring in accordance with the organization-level continuous monitoring strategy that includes:

# Statement

Develop a system-level continuous monitoring strategy and implement continuous monitoring in accordance with the organization-level continuous monitoring strategy that includes:

# Guidance

Continuous monitoring at the system level facilitates ongoing awareness of the system security and privacy posture to support organizational risk management decisions. The terms "continuous" and "ongoing" imply that organizations assess and monitor their controls and risks at a frequency sufficient to support risk-based decisions. Different types of controls may require different monitoring frequencies. The results of continuous monitoring generate risk response actions by organizations. When monitoring the effectiveness of multiple controls that have been grouped into capabilities, a root-cause analysis may be needed to determine the specific control that has failed. Continuous monitoring programs allow organizations to maintain the authorizations of systems and common controls in highly dynamic environments of operation with changing mission and business needs, threats, vulnerabilities, and technologies. Having access to security and privacy information on a continuing basis through reports and dashboards gives organizational officials the ability to make effective and timely risk management decisions, including ongoing authorization decisions.

Automation supports more frequent updates to hardware, software, and firmware inventories, authorization packages, and other system information. Effectiveness is further enhanced when continuous monitoring outputs are formatted to provide information that is specific, measurable, actionable, relevant, and timely. Continuous monitoring activities are scaled in accordance with the security categories of systems. Monitoring requirements, including the need for specific monitoring, may be referenced in other controls and control enhancements, such as [AC-2g](#ac-2_smt.g), [AC-2(7)](#ac-2.7), [AC-2(12)(a)](#ac-2.12_smt.a), [AC-2(7)(b)](#ac-2.7_smt.b), [AC-2(7)(c)](#ac-2.7_smt.c), [AC-17(1)](#ac-17.1), [AT-4a](#at-4_smt.a), [AU-13](#au-13), [AU-13(1)](#au-13.1), [AU-13(2)](#au-13.2), [CM-3f](#cm-3_smt.f), [CM-6d](#cm-6_smt.d), [CM-11c](#cm-11_smt.c), [IR-5](#ir-5), [MA-2b](#ma-2_smt.b), [MA-3a](#ma-3_smt.a), [MA-4a](#ma-4_smt.a), [PE-3d](#pe-3_smt.d), [PE-6](#pe-6), [PE-14b](#pe-14_smt.b), [PE-16](#pe-16), [PE-20](#pe-20), [PM-6](#pm-6), [PM-23](#pm-23), [PM-31](#pm-31), [PS-7e](#ps-7_smt.e), [SA-9c](#sa-9_smt.c), [SR-4](#sr-4), [SC-5(3)(b)](#sc-5.3_smt.b), [SC-7a](#sc-7_smt.a), [SC-7(24)(b)](#sc-7.24_smt.b), [SC-18b](#sc-18_smt.b), [SC-43b](#sc-43_smt.b) , and [SI-4](#si-4).

# Parameters

- `ca-7_prm_4`
- `ca-7_prm_5`
- `ca-07_odp.01`
- `ca-07_odp.02`
- `ca-07_odp.03`
- `ca-07_odp.04`
- `ca-07_odp.05`
- `ca-07_odp.06`
- `ca-07_odp.07`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
