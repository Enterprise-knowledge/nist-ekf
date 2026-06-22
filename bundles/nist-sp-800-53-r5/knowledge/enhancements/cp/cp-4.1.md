---
type: control_enhancement
title: CP-4.1 - Coordinate with Related Plans
description: Coordinate contingency plan testing with organizational elements responsible for related plans.
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
- cp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-4.md
  relation: part_of
  description: CP-4.1 - Coordinate with Related Plans is part of its parent SP 800-53 structure.
- name: CP-4 - Contingency Plan Testing
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-4.md
  relation: enhances
  description: CP-4.1 enhances base control CP-4.
nist_id: CP-4.1
sort_id: cp-04.01
implementation_level: organization
parameter_ids: []
reference_links:
- '#cp-4'
- '#ir-8'
- '#pm-8'
---

# Summary

Coordinate contingency plan testing with organizational elements responsible for related plans.

# Statement

Coordinate contingency plan testing with organizational elements responsible for related plans.

# Guidance

Plans related to contingency planning for organizational systems include Business Continuity Plans, Disaster Recovery Plans, Continuity of Operations Plans, Crisis Communications Plans, Critical Infrastructure Plans, Cyber Incident Response Plans, and Occupant Emergency Plans. Coordination of contingency plan testing does not require organizations to create organizational elements to handle related plans or to align such elements with specific plans. However, it does require that if such organizational elements are responsible for related plans, organizations coordinate with those elements.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
