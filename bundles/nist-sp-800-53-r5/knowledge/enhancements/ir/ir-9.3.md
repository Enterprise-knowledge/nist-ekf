---
type: control_enhancement
title: IR-9.3 - Post-spill Operations
description: 'Implement the following procedures to ensure that organizational personnel impacted by information
  spills can continue to carry out assigned tasks while contaminated systems are undergoing corrective actions:
  {{ insert: '
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-9.md
  relation: part_of
  description: IR-9.3 - Post-spill Operations is part of its parent SP 800-53 structure.
- name: IR-9 - Information Spillage Response
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-9.md
  relation: enhances
  description: IR-9.3 enhances base control IR-9.
nist_id: IR-9.3
sort_id: ir-09.03
implementation_level: organization
parameter_ids:
- ir-09.03_odp
reference_links:
- '#ir-9'
---

# Summary

Implement the following procedures to ensure that organizational personnel impacted by information spills can continue to carry out assigned tasks while contaminated systems are undergoing corrective actions: {{ insert: 

# Statement

Implement the following procedures to ensure that organizational personnel impacted by information spills can continue to carry out assigned tasks while contaminated systems are undergoing corrective actions: {{ insert: param, ir-09.03_odp }}.

# Guidance

Corrective actions for systems contaminated due to information spillages may be time-consuming. Personnel may not have access to the contaminated systems while corrective actions are being taken, which may potentially affect their ability to conduct organizational business.

# Parameters

- `ir-09.03_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
