---
type: control
title: CM-6 - Configuration Settings
description: SP 800-53 control CM-6.
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
- cm
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/cm.md
  relation: part_of
  description: CM-6 - Configuration Settings is part of its parent SP 800-53 structure.
- name: CM-6.1 - Automated Management, Application, and Verification
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-6.1.md
  relation: has_enhancement
  description: CM-6 has enhancement CM-6.1.
- name: CM-6.2 - Respond to Unauthorized Changes
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-6.2.md
  relation: has_enhancement
  description: CM-6 has enhancement CM-6.2.
- name: CM-6.3 - Unauthorized Change Detection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-6.3.md
  relation: has_enhancement
  description: CM-6 has enhancement CM-6.3.
- name: CM-6.4 - Conformance Demonstration
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-6.4.md
  relation: has_enhancement
  description: CM-6 has enhancement CM-6.4.
nist_id: CM-6
sort_id: cm-06
implementation_level: organization
parameter_ids:
- cm-06_odp.01
- cm-06_odp.02
- cm-06_odp.03
reference_links:
- '#4895b4cd-34c5-4667-bf8a-27d443c12047'
- '#8016d2ed-d30f-4416-9c45-0f42c7aa3232'
- '#20db4e66-e257-450c-b2e4-2bb9a62a2c88'
- '#98498928-3ca3-44b3-8b1e-f48685373087'
- '#d744d9a3-73eb-4085-b9ff-79e82e9e2d6e'
- '#aa66e14f-e7cb-4a37-99d2-07578dfd4608'
- '#ac-3'
- '#ac-19'
- '#au-2'
- '#au-6'
- '#ca-9'
- '#cm-2'
- '#cm-3'
- '#cm-5'
- '#cm-7'
- '#cm-11'
- '#cp-7'
- '#cp-9'
- '#cp-10'
- '#ia-3'
- '#ia-5'
- '#pl-8'
- '#pl-9'
- '#ra-5'
- '#sa-4'
- '#sa-5'
- '#sa-8'
- '#sa-9'
- '#sc-18'
- '#sc-28'
- '#sc-43'
- '#si-2'
- '#si-4'
- '#si-6'
---

# Summary

SP 800-53 control CM-6.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Configuration settings are the parameters that can be changed in the hardware, software, or firmware components of the system that affect the security and privacy posture or functionality of the system. Information technology products for which configuration settings can be defined include mainframe computers, servers, workstations, operating systems, mobile devices, input/output devices, protocols, and applications. Parameters that impact the security posture of systems include registry settings; account, file, or directory permission settings; and settings for functions, protocols, ports, services, and remote connections. Privacy parameters are parameters impacting the privacy posture of systems, including the parameters required to satisfy other privacy controls. Privacy parameters include settings for access controls, data processing preferences, and processing and retention permissions. Organizations establish organization-wide configuration settings and subsequently derive specific configuration settings for systems. The established settings become part of the configuration baseline for the system.

Common secure configurations (also known as security configuration checklists, lockdown and hardening guides, and security reference guides) provide recognized, standardized, and established benchmarks that stipulate secure configuration settings for information technology products and platforms as well as instructions for configuring those products or platforms to meet operational requirements. Common secure configurations can be developed by a variety of organizations, including information technology product developers, manufacturers, vendors, federal agencies, consortia, academia, industry, and other organizations in the public and private sectors.

Implementation of a common secure configuration may be mandated at the organization level, mission and business process level, system level, or at a higher level, including by a regulatory agency. Common secure configurations include the United States Government Configuration Baseline [USGCB](#98498928-3ca3-44b3-8b1e-f48685373087) and security technical implementation guides (STIGs), which affect the implementation of [CM-6](#cm-6) and other controls such as [AC-19](#ac-19) and [CM-7](#cm-7) . The Security Content Automation Protocol (SCAP) and the defined standards within the protocol provide an effective method to uniquely identify, track, and control configuration settings.

# Parameters

- `cm-06_odp.01`
- `cm-06_odp.02`
- `cm-06_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
