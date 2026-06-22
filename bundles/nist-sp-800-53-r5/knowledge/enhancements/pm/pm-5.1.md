---
type: control_enhancement
title: PM-5.1 - Inventory of Personally Identifiable Information
description: 'Establish, maintain, and update {{ insert: param, pm-05.01_odp }} an inventory of all systems, applications,
  and projects that process personally identifiable information.'
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
- pm
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pm/pm-5.md
  relation: part_of
  description: PM-5.1 - Inventory of Personally Identifiable Information is part of its parent SP 800-53 structure.
- name: PM-5 - System Inventory
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pm/pm-5.md
  relation: enhances
  description: PM-5.1 enhances base control PM-5.
nist_id: PM-5.1
sort_id: pm-05.01
implementation_level: organization
parameter_ids:
- pm-05.01_odp
reference_links:
- '#pm-5'
- '#ac-3'
- '#cm-8'
- '#cm-12'
- '#cm-13'
- '#pl-8'
- '#pm-22'
- '#pt-3'
- '#pt-5'
- '#si-12'
- '#si-18'
---

# Summary

Establish, maintain, and update {{ insert: param, pm-05.01_odp }} an inventory of all systems, applications, and projects that process personally identifiable information.

# Statement

Establish, maintain, and update {{ insert: param, pm-05.01_odp }} an inventory of all systems, applications, and projects that process personally identifiable information.

# Guidance

An inventory of systems, applications, and projects that process personally identifiable information supports the mapping of data actions, providing individuals with privacy notices, maintaining accurate personally identifiable information, and limiting the processing of personally identifiable information when such information is not needed for operational purposes. Organizations may use this inventory to ensure that systems only process the personally identifiable information for authorized purposes and that this processing is still relevant and necessary for the purpose specified therein.

# Parameters

- `pm-05.01_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
