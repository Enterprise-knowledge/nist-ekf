---
type: control_enhancement
title: MP-4.2 - Automated Restricted Access
description: 'Restrict access to media storage areas and log access attempts and access granted using {{ insert:
  param, mp-4.2_prm_1 }}.'
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
- mp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-4.md
  relation: part_of
  description: MP-4.2 - Automated Restricted Access is part of its parent SP 800-53 structure.
- name: MP-4 - Media Storage
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-4.md
  relation: enhances
  description: MP-4.2 enhances base control MP-4.
nist_id: MP-4.2
sort_id: mp-04.02
implementation_level: organization
parameter_ids:
- mp-4.2_prm_1
- mp-04.02_odp.01
- mp-04.02_odp.02
- mp-04.02_odp.03
reference_links:
- '#mp-4'
- '#ac-3'
- '#au-2'
- '#au-6'
- '#au-9'
- '#au-12'
- '#pe-3'
---

# Summary

Restrict access to media storage areas and log access attempts and access granted using {{ insert: param, mp-4.2_prm_1 }}.

# Statement

Restrict access to media storage areas and log access attempts and access granted using {{ insert: param, mp-4.2_prm_1 }}.

# Guidance

Automated mechanisms include keypads, biometric readers, or card readers on the external entries to media storage areas.

# Parameters

- `mp-4.2_prm_1`
- `mp-04.02_odp.01`
- `mp-04.02_odp.02`
- `mp-04.02_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
