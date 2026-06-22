---
type: control_enhancement
title: AU-9.5 - Dual Authorization
description: 'Enforce dual authorization for {{ insert: param, au-09.05_odp.01 }} of {{ insert: param, au-09.05_odp.02
  }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-9.md
  relation: part_of
  description: AU-9.5 - Dual Authorization is part of its parent SP 800-53 structure.
- name: AU-9 - Protection of Audit Information
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-9.md
  relation: enhances
  description: AU-9.5 enhances base control AU-9.
nist_id: AU-9.5
sort_id: au-09.05
implementation_level: organization
parameter_ids:
- au-09.05_odp.01
- au-09.05_odp.02
reference_links:
- '#au-9'
- '#ac-3'
---

# Summary

Enforce dual authorization for {{ insert: param, au-09.05_odp.01 }} of {{ insert: param, au-09.05_odp.02 }}.

# Statement

Enforce dual authorization for {{ insert: param, au-09.05_odp.01 }} of {{ insert: param, au-09.05_odp.02 }}.

# Guidance

Organizations may choose different selection options for different types of audit information. Dual authorization mechanisms (also known as two-person control) require the approval of two authorized individuals to execute audit functions. To reduce the risk of collusion, organizations consider rotating dual authorization duties to other individuals. Organizations do not require dual authorization mechanisms when immediate responses are necessary to ensure public and environmental safety.

# Parameters

- `au-09.05_odp.01`
- `au-09.05_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
