---
type: control
title: PT-7 - Specific Categories of Personally Identifiable Information
description: 'Apply {{ insert: param, pt-07_odp }} for specific categories of personally identifiable information.'
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
  description: PT-7 - Specific Categories of Personally Identifiable Information is part of its parent SP 800-53
    structure.
- name: PT-7.1 - Social Security Numbers
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pt/pt-7.1.md
  relation: has_enhancement
  description: PT-7 has enhancement PT-7.1.
- name: PT-7.2 - First Amendment Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pt/pt-7.2.md
  relation: has_enhancement
  description: PT-7 has enhancement PT-7.2.
nist_id: PT-7
sort_id: pt-07
implementation_level: organization
parameter_ids:
- pt-07_odp
reference_links:
- '#18e71fec-c6fd-475a-925a-5d8495cf8455'
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#3671ff20-c17c-44d6-8a88-7de203fa74aa'
- '#c28ae9a8-1121-42a9-a85e-00cfcc9b9a94'
- '#ir-9'
- '#pt-2'
- '#pt-3'
- '#ra-3'
---

# Summary

Apply {{ insert: param, pt-07_odp }} for specific categories of personally identifiable information.

# Statement

Apply {{ insert: param, pt-07_odp }} for specific categories of personally identifiable information.

# Guidance

Organizations apply any conditions or protections that may be necessary for specific categories of personally identifiable information. These conditions may be required by laws, executive orders, directives, regulations, policies, standards, or guidelines. The requirements may also come from the results of privacy risk assessments that factor in contextual changes that may result in an organizational determination that a particular category of personally identifiable information is particularly sensitive or raises particular privacy risks. Organizations consult with the senior agency official for privacy and legal counsel regarding any protections that may be necessary.

# Parameters

- `pt-07_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
