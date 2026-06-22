---
type: control_enhancement
title: SA-9.5 - Processing, Storage, and Service Location
description: 'Restrict the location of {{ insert: param, sa-09.05_odp.01 }} to {{ insert: param, sa-09.05_odp.02
  }} based on {{ insert: param, sa-09.05_odp.03 }}.'
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
- sa
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-9.md
  relation: part_of
  description: SA-9.5 - Processing, Storage, and Service Location is part of its parent SP 800-53 structure.
- name: SA-9 - External System Services
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-9.md
  relation: enhances
  description: SA-9.5 enhances base control SA-9.
nist_id: SA-9.5
sort_id: sa-09.05
implementation_level: organization
parameter_ids:
- sa-09.05_odp.01
- sa-09.05_odp.02
- sa-09.05_odp.03
reference_links:
- '#sa-9'
- '#sa-5'
- '#sr-4'
---

# Summary

Restrict the location of {{ insert: param, sa-09.05_odp.01 }} to {{ insert: param, sa-09.05_odp.02 }} based on {{ insert: param, sa-09.05_odp.03 }}.

# Statement

Restrict the location of {{ insert: param, sa-09.05_odp.01 }} to {{ insert: param, sa-09.05_odp.02 }} based on {{ insert: param, sa-09.05_odp.03 }}.

# Guidance

The location of information processing, information and data storage, or system services can have a direct impact on the ability of organizations to successfully execute their mission and business functions. The impact occurs when external providers control the location of processing, storage, or services. The criteria that external providers use for the selection of processing, storage, or service locations may be different from the criteria that organizations use. For example, organizations may desire that data or information storage locations be restricted to certain locations to help facilitate incident response activities in case of information security incidents or breaches. Incident response activities, including forensic analyses and after-the-fact investigations, may be adversely affected by the governing laws, policies, or protocols in the locations where processing and storage occur and/or the locations from which system services emanate.

# Parameters

- `sa-09.05_odp.01`
- `sa-09.05_odp.02`
- `sa-09.05_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
