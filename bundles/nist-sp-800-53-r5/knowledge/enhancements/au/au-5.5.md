---
type: control_enhancement
title: AU-5.5 - Alternate Audit Logging Capability
description: 'Provide an alternate audit logging capability in the event of a failure in primary audit logging capability
  that implements {{ insert: param, au-05.05_odp }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-5.md
  relation: part_of
  description: AU-5.5 - Alternate Audit Logging Capability is part of its parent SP 800-53 structure.
- name: AU-5 - Response to Audit Logging Process Failures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-5.md
  relation: enhances
  description: AU-5.5 enhances base control AU-5.
nist_id: AU-5.5
sort_id: au-05.05
implementation_level: organization
parameter_ids:
- au-05.05_odp
reference_links:
- '#au-5'
- '#au-9'
---

# Summary

Provide an alternate audit logging capability in the event of a failure in primary audit logging capability that implements {{ insert: param, au-05.05_odp }}.

# Statement

Provide an alternate audit logging capability in the event of a failure in primary audit logging capability that implements {{ insert: param, au-05.05_odp }}.

# Guidance

Since an alternate audit logging capability may be a short-term protection solution employed until the failure in the primary audit logging capability is corrected, organizations may determine that the alternate audit logging capability need only provide a subset of the primary audit logging functionality that is impacted by the failure.

# Parameters

- `au-05.05_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
