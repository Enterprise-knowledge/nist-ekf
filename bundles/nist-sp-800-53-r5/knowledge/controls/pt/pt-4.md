---
type: control
title: PT-4 - Consent
description: 'Implement {{ insert: param, pt-04_odp }} for individuals to consent to the processing of their personally
  identifiable information prior to its collection that facilitate individuals’ informed decision-making.'
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
  description: PT-4 - Consent is part of its parent SP 800-53 structure.
- name: PT-4.1 - Tailored Consent
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pt/pt-4.1.md
  relation: has_enhancement
  description: PT-4 has enhancement PT-4.1.
- name: PT-4.2 - Just-in-time Consent
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pt/pt-4.2.md
  relation: has_enhancement
  description: PT-4 has enhancement PT-4.2.
- name: PT-4.3 - Revocation
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pt/pt-4.3.md
  relation: has_enhancement
  description: PT-4 has enhancement PT-4.3.
nist_id: PT-4
sort_id: pt-04
implementation_level: organization
parameter_ids:
- pt-04_odp
reference_links:
- '#18e71fec-c6fd-475a-925a-5d8495cf8455'
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#737513fa-6758-403f-831d-5ddab5e23cb3'
- '#ac-16'
- '#pt-2'
- '#pt-5'
---

# Summary

Implement {{ insert: param, pt-04_odp }} for individuals to consent to the processing of their personally identifiable information prior to its collection that facilitate individuals’ informed decision-making.

# Statement

Implement {{ insert: param, pt-04_odp }} for individuals to consent to the processing of their personally identifiable information prior to its collection that facilitate individuals’ informed decision-making.

# Guidance

Consent allows individuals to participate in making decisions about the processing of their information and transfers some of the risk that arises from the processing of personally identifiable information from the organization to an individual. Consent may be required by applicable laws, executive orders, directives, regulations, policies, standards, or guidelines. Otherwise, when selecting consent as a control, organizations consider whether individuals can be reasonably expected to understand and accept the privacy risks that arise from their authorization. Organizations consider whether other controls may more effectively mitigate privacy risk either alone or in conjunction with consent. Organizations also consider any demographic or contextual factors that may influence the understanding or behavior of individuals with respect to the processing carried out by the system or organization. When soliciting consent from individuals, organizations consider the appropriate mechanism for obtaining consent, including the type of consent (e.g., opt-in, opt-out), how to properly authenticate and identity proof individuals and how to obtain consent through electronic means. In addition, organizations consider providing a mechanism for individuals to revoke consent once it has been provided, as appropriate. Finally, organizations consider usability factors to help individuals understand the risks being accepted when providing consent, including the use of plain language and avoiding technical jargon.

# Parameters

- `pt-04_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
