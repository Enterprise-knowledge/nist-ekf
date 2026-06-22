---
type: control
title: IR-5 - Incident Monitoring
description: Track and document incidents.
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
- ir
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ir.md
  relation: part_of
  description: IR-5 - Incident Monitoring is part of its parent SP 800-53 structure.
- name: IR-5.1 - Automated Tracking, Data Collection, and Analysis
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-5.1.md
  relation: has_enhancement
  description: IR-5 has enhancement IR-5.1.
nist_id: IR-5
sort_id: ir-05
implementation_level: organization
parameter_ids: []
reference_links:
- '#49b8aa2d-a88c-4bff-9f20-876ccb8f7dcb'
- '#au-6'
- '#au-7'
- '#ir-4'
- '#ir-6'
- '#ir-8'
- '#pe-6'
- '#pm-5'
- '#sc-5'
- '#sc-7'
- '#si-3'
- '#si-4'
- '#si-7'
---

# Summary

Track and document incidents.

# Statement

Track and document incidents.

# Guidance

Documenting incidents includes maintaining records about each incident, the status of the incident, and other pertinent information necessary for forensics as well as evaluating incident details, trends, and handling. Incident information can be obtained from a variety of sources, including network monitoring, incident reports, incident response teams, user complaints, supply chain partners, audit monitoring, physical access monitoring, and user and administrator reports. [IR-4](#ir-4) provides information on the types of incidents that are appropriate for monitoring.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
