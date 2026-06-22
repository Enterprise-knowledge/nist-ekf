---
type: control_enhancement
title: AC-3.14 - Individual Access
description: 'Provide {{ insert: param, ac-03.14_odp.01 }} to enable individuals to have access to the following
  elements of their personally identifiable information: {{ insert: param, ac-03.14_odp.02 }}.'
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
  description: AC-3.14 - Individual Access is part of its parent SP 800-53 structure.
- name: AC-3 - Access Enforcement
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-3.md
  relation: enhances
  description: AC-3.14 enhances base control AC-3.
nist_id: AC-3.14
sort_id: ac-03.14
implementation_level: system
parameter_ids:
- ac-03.14_odp.01
- ac-03.14_odp.02
reference_links:
- '#ac-3'
- '#ia-8'
- '#pm-22'
- '#pm-20'
- '#pm-21'
- '#pt-6'
---

# Summary

Provide {{ insert: param, ac-03.14_odp.01 }} to enable individuals to have access to the following elements of their personally identifiable information: {{ insert: param, ac-03.14_odp.02 }}.

# Statement

Provide {{ insert: param, ac-03.14_odp.01 }} to enable individuals to have access to the following elements of their personally identifiable information: {{ insert: param, ac-03.14_odp.02 }}.

# Guidance

Individual access affords individuals the ability to review personally identifiable information about them held within organizational records, regardless of format. Access helps individuals to develop an understanding about how their personally identifiable information is being processed. It can also help individuals ensure that their data is accurate. Access mechanisms can include request forms and application interfaces. For federal agencies, [PRIVACT](#18e71fec-c6fd-475a-925a-5d8495cf8455) processes can be located in systems of record notices and on agency websites. Access to certain types of records may not be appropriate (e.g., for federal agencies, law enforcement records within a system of records may be exempt from disclosure under the [PRIVACT](#18e71fec-c6fd-475a-925a-5d8495cf8455) ) or may require certain levels of authentication assurance. Organizational personnel consult with the senior agency official for privacy and legal counsel to determine appropriate mechanisms and access rights or limitations.

# Parameters

- `ac-03.14_odp.01`
- `ac-03.14_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
