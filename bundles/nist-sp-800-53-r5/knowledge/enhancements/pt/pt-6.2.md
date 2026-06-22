---
type: control_enhancement
title: PT-6.2 - Exemption Rules
description: 'Review all Privacy Act exemptions claimed for the system of records at {{ insert: param, pt-06.02_odp
  }} to ensure they remain appropriate and necessary in accordance with law, that they have been promulgated as
  regulati'
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
  description: PT-6.2 - Exemption Rules is part of its parent SP 800-53 structure.
- name: PT-6 - System of Records Notice
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-6.md
  relation: enhances
  description: PT-6.2 enhances base control PT-6.
nist_id: PT-6.2
sort_id: pt-06.02
implementation_level: organization
parameter_ids:
- pt-06.02_odp
reference_links:
- '#pt-6'
---

# Summary

Review all Privacy Act exemptions claimed for the system of records at {{ insert: param, pt-06.02_odp }} to ensure they remain appropriate and necessary in accordance with law, that they have been promulgated as regulati

# Statement

Review all Privacy Act exemptions claimed for the system of records at {{ insert: param, pt-06.02_odp }} to ensure they remain appropriate and necessary in accordance with law, that they have been promulgated as regulations, and that they are accurately described in the system of records notice.

# Guidance

The [PRIVACT](#18e71fec-c6fd-475a-925a-5d8495cf8455) includes two sets of provisions that allow federal agencies to claim exemptions from certain requirements in the statute. In certain circumstances, these provisions allow agencies to promulgate regulations to exempt a system of records from select provisions of the [PRIVACT](#18e71fec-c6fd-475a-925a-5d8495cf8455) . At a minimum, organizations’ [PRIVACT](#18e71fec-c6fd-475a-925a-5d8495cf8455) exemption regulations include the specific name(s) of any system(s) of records that will be exempt, the specific provisions of the [PRIVACT](#18e71fec-c6fd-475a-925a-5d8495cf8455) from which the system(s) of records is to be exempted, the reasons for the exemption, and an explanation for why the exemption is both necessary and appropriate.

# Parameters

- `pt-06.02_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
