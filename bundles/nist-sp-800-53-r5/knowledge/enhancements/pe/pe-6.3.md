---
type: control_enhancement
title: PE-6.3 - Video Surveillance
description: SP 800-53 control PE-6.3.
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
- pe
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-6.md
  relation: part_of
  description: PE-6.3 - Video Surveillance is part of its parent SP 800-53 structure.
- name: PE-6 - Monitoring Physical Access
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-6.md
  relation: enhances
  description: PE-6.3 enhances base control PE-6.
nist_id: PE-6.3
sort_id: pe-06.03
implementation_level: organization
parameter_ids:
- pe-06.03_odp.01
- pe-06.03_odp.02
- pe-06.03_odp.03
reference_links:
- '#pe-6'
---

# Summary

SP 800-53 control PE-6.3.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Video surveillance focuses on recording activity in specified areas for the purposes of subsequent review, if circumstances so warrant. Video recordings are typically reviewed to detect anomalous events or incidents. Monitoring the surveillance video is not required, although organizations may choose to do so. There may be legal considerations when performing and retaining video surveillance, especially if such surveillance is in a public location.

# Parameters

- `pe-06.03_odp.01`
- `pe-06.03_odp.02`
- `pe-06.03_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
