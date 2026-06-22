---
type: control_enhancement
title: PT-4.2 - Just-in-time Consent
description: 'Present {{ insert: param, pt-04.02_odp.01 }} to individuals at {{ insert: param, pt-04.02_odp.02 }}
  and in conjunction with {{ insert: param, pt-04.02_odp.03 }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-4.md
  relation: part_of
  description: PT-4.2 - Just-in-time Consent is part of its parent SP 800-53 structure.
- name: PT-4 - Consent
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-4.md
  relation: enhances
  description: PT-4.2 enhances base control PT-4.
nist_id: PT-4.2
sort_id: pt-04.02
implementation_level: organization
parameter_ids:
- pt-04.02_odp.01
- pt-04.02_odp.02
- pt-04.02_odp.03
reference_links:
- '#pt-4'
- '#pt-2'
---

# Summary

Present {{ insert: param, pt-04.02_odp.01 }} to individuals at {{ insert: param, pt-04.02_odp.02 }} and in conjunction with {{ insert: param, pt-04.02_odp.03 }}.

# Statement

Present {{ insert: param, pt-04.02_odp.01 }} to individuals at {{ insert: param, pt-04.02_odp.02 }} and in conjunction with {{ insert: param, pt-04.02_odp.03 }}.

# Guidance

Just-in-time consent enables individuals to participate in how their personally identifiable information is being processed at the time or in conjunction with specific types of data processing when such participation may be most useful to the individual. Individual assumptions about how personally identifiable information is being processed might not be accurate or reliable if time has passed since the individual last gave consent or the type of processing creates significant privacy risk. Organizations use discretion to determine when to use just-in-time consent and may use supporting information on demographics, focus groups, or surveys to learn more about individuals’ privacy interests and concerns.

# Parameters

- `pt-04.02_odp.01`
- `pt-04.02_odp.02`
- `pt-04.02_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
