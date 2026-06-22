---
type: control
title: PT-3 - Personally Identifiable Information Processing Purposes
description: SP 800-53 control PT-3.
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
- pt
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/pt.md
  relation: part_of
  description: PT-3 - Personally Identifiable Information Processing Purposes is part of its parent SP 800-53 structure.
- name: PT-3.1 - Data Tagging
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pt/pt-3.1.md
  relation: has_enhancement
  description: PT-3 has enhancement PT-3.1.
- name: PT-3.2 - Automation
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pt/pt-3.2.md
  relation: has_enhancement
  description: PT-3 has enhancement PT-3.2.
nist_id: PT-3
sort_id: pt-03
implementation_level: organization
parameter_ids:
- pt-03_odp.01
- pt-03_odp.02
- pt-03_odp.03
- pt-03_odp.04
reference_links:
- '#18e71fec-c6fd-475a-925a-5d8495cf8455'
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#a2590922-82f3-4277-83c0-ca5bee06dba4'
- '#ac-2'
- '#ac-3'
- '#at-3'
- '#cm-13'
- '#ir-9'
- '#pm-9'
- '#pm-25'
- '#pt-2'
- '#pt-5'
- '#pt-6'
- '#pt-7'
- '#ra-8'
- '#sc-43'
- '#si-12'
- '#si-18'
---

# Summary

SP 800-53 control PT-3.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Identifying and documenting the purpose for processing provides organizations with a basis for understanding why personally identifiable information may be processed. The term "process" includes every step of the information life cycle, including creation, collection, use, processing, storage, maintenance, dissemination, disclosure, and disposal. Identifying and documenting the purpose of processing is a prerequisite to enabling owners and operators of the system and individuals whose information is processed by the system to understand how the information will be processed. This enables individuals to make informed decisions about their engagement with information systems and organizations and to manage their privacy interests. Once the specific processing purpose has been identified, the purpose is described in the organization’s privacy notices, policies, and any related privacy compliance documentation, including privacy impact assessments, system of records notices, [PRIVACT](#18e71fec-c6fd-475a-925a-5d8495cf8455) statements, computer matching notices, and other applicable Federal Register notices.

Organizations take steps to help ensure that personally identifiable information is processed only for identified purposes, including training organizational personnel and monitoring and auditing organizational processing of personally identifiable information.

Organizations monitor for changes in personally identifiable information processing. Organizational personnel consult with the senior agency official for privacy and legal counsel to ensure that any new purposes that arise from changes in processing are compatible with the purpose for which the information was collected, or if the new purpose is not compatible, implement mechanisms in accordance with defined requirements to allow for the new processing, if appropriate. Mechanisms may include obtaining consent from individuals, revising privacy policies, or other measures to manage privacy risks that arise from changes in personally identifiable information processing purposes.

# Parameters

- `pt-03_odp.01`
- `pt-03_odp.02`
- `pt-03_odp.03`
- `pt-03_odp.04`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
