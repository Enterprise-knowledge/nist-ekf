---
type: control_enhancement
title: CA-8.3 - Facility Penetration Testing
description: 'Employ a penetration testing process that includes {{ insert: param, ca-08.03_odp.01 }} {{ insert:
  param, ca-08.03_odp.02 }} attempts to bypass or circumvent controls associated with physical access points to
  the facilit'
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
- ca
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ca/ca-8.md
  relation: part_of
  description: CA-8.3 - Facility Penetration Testing is part of its parent SP 800-53 structure.
- name: CA-8 - Penetration Testing
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ca/ca-8.md
  relation: enhances
  description: CA-8.3 enhances base control CA-8.
nist_id: CA-8.3
sort_id: ca-08.03
implementation_level: organization
parameter_ids:
- ca-08.03_odp.01
- ca-08.03_odp.02
reference_links:
- '#ca-8'
- '#ca-2'
- '#pe-3'
---

# Summary

Employ a penetration testing process that includes {{ insert: param, ca-08.03_odp.01 }} {{ insert: param, ca-08.03_odp.02 }} attempts to bypass or circumvent controls associated with physical access points to the facilit

# Statement

Employ a penetration testing process that includes {{ insert: param, ca-08.03_odp.01 }} {{ insert: param, ca-08.03_odp.02 }} attempts to bypass or circumvent controls associated with physical access points to the facility.

# Guidance

Penetration testing of physical access points can provide information on critical vulnerabilities in the operating environments of organizational systems. Such information can be used to correct weaknesses or deficiencies in physical controls that are necessary to protect organizational systems.

# Parameters

- `ca-08.03_odp.01`
- `ca-08.03_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
