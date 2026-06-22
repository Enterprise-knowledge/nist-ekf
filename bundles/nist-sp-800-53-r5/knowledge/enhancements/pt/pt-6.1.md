---
type: control_enhancement
title: PT-6.1 - Routine Uses
description: 'Review all routine uses published in the system of records notice at {{ insert: param, pt-06.01_odp
  }} to ensure continued accuracy, and to ensure that routine uses continue to be compatible with the purpose for
  which th'
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-6.md
  relation: part_of
  description: PT-6.1 - Routine Uses is part of its parent SP 800-53 structure.
- name: PT-6 - System of Records Notice
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-6.md
  relation: enhances
  description: PT-6.1 enhances base control PT-6.
nist_id: PT-6.1
sort_id: pt-06.01
implementation_level: organization
parameter_ids:
- pt-06.01_odp
reference_links:
- '#pt-6'
---

# Summary

Review all routine uses published in the system of records notice at {{ insert: param, pt-06.01_odp }} to ensure continued accuracy, and to ensure that routine uses continue to be compatible with the purpose for which th

# Statement

Review all routine uses published in the system of records notice at {{ insert: param, pt-06.01_odp }} to ensure continued accuracy, and to ensure that routine uses continue to be compatible with the purpose for which the information was collected.

# Guidance

A [PRIVACT](#18e71fec-c6fd-475a-925a-5d8495cf8455) routine use is a particular kind of disclosure of a record outside of the federal agency maintaining the system of records. A routine use is an exception to the [PRIVACT](#18e71fec-c6fd-475a-925a-5d8495cf8455) prohibition on the disclosure of a record in a system of records without the prior written consent of the individual to whom the record pertains. To qualify as a routine use, the disclosure must be for a purpose that is compatible with the purpose for which the information was originally collected. The [PRIVACT](#18e71fec-c6fd-475a-925a-5d8495cf8455) requires agencies to describe each routine use of the records maintained in the system of records, including the categories of users of the records and the purpose of the use. Agencies may only establish routine uses by explicitly publishing them in the relevant system of records notice.

# Parameters

- `pt-06.01_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
