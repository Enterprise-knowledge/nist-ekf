---
type: control
title: PT-2 - Authority to Process Personally Identifiable Information
description: SP 800-53 control PT-2.
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
  description: PT-2 - Authority to Process Personally Identifiable Information is part of its parent SP 800-53 structure.
- name: PT-2.1 - Data Tagging
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pt/pt-2.1.md
  relation: has_enhancement
  description: PT-2 has enhancement PT-2.1.
- name: PT-2.2 - Automation
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pt/pt-2.2.md
  relation: has_enhancement
  description: PT-2 has enhancement PT-2.2.
nist_id: PT-2
sort_id: pt-02
implementation_level: organization
parameter_ids:
- pt-02_odp.01
- pt-02_odp.02
- pt-02_odp.03
reference_links:
- '#18e71fec-c6fd-475a-925a-5d8495cf8455'
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#a2590922-82f3-4277-83c0-ca5bee06dba4'
- '#ac-2'
- '#ac-3'
- '#cm-13'
- '#ir-9'
- '#pm-9'
- '#pm-24'
- '#pt-1'
- '#pt-3'
- '#pt-5'
- '#pt-6'
- '#ra-3'
- '#ra-8'
- '#si-12'
- '#si-18'
---

# Summary

SP 800-53 control PT-2.

# Statement

No statement text was present in the OSCAL record.

# Guidance

The processing of personally identifiable information is an operation or set of operations that the information system or organization performs with respect to personally identifiable information across the information life cycle. Processing includes but is not limited to creation, collection, use, processing, storage, maintenance, dissemination, disclosure, and disposal. Processing operations also include logging, generation, and transformation, as well as analysis techniques, such as data mining.

Organizations may be subject to laws, executive orders, directives, regulations, or policies that establish the organization’s authority and thereby limit certain types of processing of personally identifiable information or establish other requirements related to the processing. Organizational personnel consult with the senior agency official for privacy and legal counsel regarding such authority, particularly if the organization is subject to multiple jurisdictions or sources of authority. For organizations whose processing is not determined according to legal authorities, the organization’s policies and determinations govern how they process personally identifiable information. While processing of personally identifiable information may be legally permissible, privacy risks may still arise. Privacy risk assessments can identify the privacy risks associated with the authorized processing of personally identifiable information and support solutions to manage such risks.

Organizations consider applicable requirements and organizational policies to determine how to document this authority. For federal agencies, the authority to process personally identifiable information is documented in privacy policies and notices, system of records notices, privacy impact assessments, [PRIVACT](#18e71fec-c6fd-475a-925a-5d8495cf8455) statements, computer matching agreements and notices, contracts, information sharing agreements, memoranda of understanding, and other documentation.

Organizations take steps to ensure that personally identifiable information is only processed for authorized purposes, including training organizational personnel on the authorized processing of personally identifiable information and monitoring and auditing organizational use of personally identifiable information.

# Parameters

- `pt-02_odp.01`
- `pt-02_odp.02`
- `pt-02_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
