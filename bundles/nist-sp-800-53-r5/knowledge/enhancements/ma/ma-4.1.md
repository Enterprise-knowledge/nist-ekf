---
type: control_enhancement
title: MA-4.1 - Logging and Review
description: SP 800-53 control MA-4.1.
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
- ma
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-4.md
  relation: part_of
  description: MA-4.1 - Logging and Review is part of its parent SP 800-53 structure.
- name: MA-4 - Nonlocal Maintenance
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-4.md
  relation: enhances
  description: MA-4.1 enhances base control MA-4.
nist_id: MA-4.1
sort_id: ma-04.01
implementation_level: organization
parameter_ids:
- ma-4.1_prm_1
- ma-04.01_odp.01
- ma-04.01_odp.02
reference_links:
- '#ma-4'
- '#au-6'
- '#au-12'
---

# Summary

SP 800-53 control MA-4.1.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Audit logging for nonlocal maintenance is enforced by [AU-2](#au-2) . Audit events are defined in [AU-2a](#au-2_smt.a).

# Parameters

- `ma-4.1_prm_1`
- `ma-04.01_odp.01`
- `ma-04.01_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
