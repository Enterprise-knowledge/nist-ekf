---
type: control_enhancement
title: RA-3.1 - Supply Chain Risk Assessment
description: SP 800-53 control RA-3.1.
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-3.md
  relation: part_of
  description: RA-3.1 - Supply Chain Risk Assessment is part of its parent SP 800-53 structure.
- name: RA-3 - Risk Assessment
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-3.md
  relation: enhances
  description: RA-3.1 enhances base control RA-3.
nist_id: RA-3.1
sort_id: ra-03.01
implementation_level: organization
parameter_ids:
- ra-03.01_odp.01
- ra-03.01_odp.02
reference_links:
- '#ra-3'
- '#ra-2'
- '#ra-9'
- '#pm-17'
- '#pm-30'
- '#sr-2'
---

# Summary

SP 800-53 control RA-3.1.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Supply chain-related events include disruption, use of defective components, insertion of counterfeits, theft, malicious development practices, improper delivery practices, and insertion of malicious code. These events can have a significant impact on the confidentiality, integrity, or availability of a system and its information and, therefore, can also adversely impact organizational operations (including mission, functions, image, or reputation), organizational assets, individuals, other organizations, and the Nation. The supply chain-related events may be unintentional or malicious and can occur at any point during the system life cycle. An analysis of supply chain risk can help an organization identify systems or components for which additional supply chain risk mitigations are required.

# Parameters

- `ra-03.01_odp.01`
- `ra-03.01_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
