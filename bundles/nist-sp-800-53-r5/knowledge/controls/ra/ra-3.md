---
type: control
title: RA-3 - Risk Assessment
description: SP 800-53 control RA-3.
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
- ra
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ra.md
  relation: part_of
  description: RA-3 - Risk Assessment is part of its parent SP 800-53 structure.
- name: RA-3.1 - Supply Chain Risk Assessment
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ra/ra-3.1.md
  relation: has_enhancement
  description: RA-3 has enhancement RA-3.1.
- name: RA-3.2 - Use of All-source Intelligence
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ra/ra-3.2.md
  relation: has_enhancement
  description: RA-3 has enhancement RA-3.2.
- name: RA-3.3 - Dynamic Threat Awareness
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ra/ra-3.3.md
  relation: has_enhancement
  description: RA-3 has enhancement RA-3.3.
- name: RA-3.4 - Predictive Cyber Analytics
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ra/ra-3.4.md
  relation: has_enhancement
  description: RA-3 has enhancement RA-3.4.
nist_id: RA-3
sort_id: ra-03
implementation_level: organization
parameter_ids:
- ra-03_odp.01
- ra-03_odp.02
- ra-03_odp.03
- ra-03_odp.04
- ra-03_odp.05
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#08b07465-dbdc-48d6-8a0b-37279602ac16'
- '#cec037f3-8aba-4c97-84b4-4082f9e515d2'
- '#e8e84963-14fc-4c3a-be05-b412a5d37cd2'
- '#4c501da5-9d79-4cb6-ba80-97260e1ce327'
- '#98d415ca-7281-4064-9931-0c366637e324'
- '#38ff38f0-1366-4f50-a4c9-26a39aacee16'
- '#ca-3'
- '#ca-6'
- '#cm-4'
- '#cm-13'
- '#cp-6'
- '#cp-7'
- '#ia-8'
- '#ma-5'
- '#pe-3'
- '#pe-8'
- '#pe-18'
- '#pl-2'
- '#pl-10'
- '#pl-11'
- '#pm-8'
- '#pm-9'
- '#pm-28'
- '#pt-2'
- '#pt-7'
- '#ra-2'
- '#ra-5'
- '#ra-7'
- '#sa-8'
- '#sa-9'
- '#sc-38'
- '#si-12'
---

# Summary

SP 800-53 control RA-3.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Risk assessments consider threats, vulnerabilities, likelihood, and impact to organizational operations and assets, individuals, other organizations, and the Nation. Risk assessments also consider risk from external parties, including contractors who operate systems on behalf of the organization, individuals who access organizational systems, service providers, and outsourcing entities.

Organizations can conduct risk assessments at all three levels in the risk management hierarchy (i.e., organization level, mission/business process level, or information system level) and at any stage in the system development life cycle. Risk assessments can also be conducted at various steps in the Risk Management Framework, including preparation, categorization, control selection, control implementation, control assessment, authorization, and control monitoring. Risk assessment is an ongoing activity carried out throughout the system development life cycle.

Risk assessments can also address information related to the system, including system design, the intended use of the system, testing results, and supply chain-related information or artifacts. Risk assessments can play an important role in control selection processes, particularly during the application of tailoring guidance and in the earliest phases of capability determination.

# Parameters

- `ra-03_odp.01`
- `ra-03_odp.02`
- `ra-03_odp.03`
- `ra-03_odp.04`
- `ra-03_odp.05`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
