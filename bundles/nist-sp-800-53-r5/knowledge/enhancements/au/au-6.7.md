---
type: control_enhancement
title: AU-6.7 - Permitted Actions
description: 'Specify the permitted actions for each {{ insert: param, au-06.07_odp }} associated with the review,
  analysis, and reporting of audit record information.'
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
- au
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-6.md
  relation: part_of
  description: AU-6.7 - Permitted Actions is part of its parent SP 800-53 structure.
- name: AU-6 - Audit Record Review, Analysis, and Reporting
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-6.md
  relation: enhances
  description: AU-6.7 enhances base control AU-6.
nist_id: AU-6.7
sort_id: au-06.07
implementation_level: organization
parameter_ids:
- au-06.07_odp
reference_links:
- '#au-6'
---

# Summary

Specify the permitted actions for each {{ insert: param, au-06.07_odp }} associated with the review, analysis, and reporting of audit record information.

# Statement

Specify the permitted actions for each {{ insert: param, au-06.07_odp }} associated with the review, analysis, and reporting of audit record information.

# Guidance

Organizations specify permitted actions for system processes, roles, and users associated with the review, analysis, and reporting of audit records through system account management activities. Specifying permitted actions on audit record information is a way to enforce the principle of least privilege. Permitted actions are enforced by the system and include read, write, execute, append, and delete.

# Parameters

- `au-06.07_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
