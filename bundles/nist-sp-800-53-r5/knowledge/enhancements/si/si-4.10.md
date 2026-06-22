---
type: control_enhancement
title: SI-4.10 - Visibility of Encrypted Communications
description: 'Make provisions so that {{ insert: param, si-04.10_odp.01 }} is visible to {{ insert: param, si-04.10_odp.02
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
- si
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-4.md
  relation: part_of
  description: SI-4.10 - Visibility of Encrypted Communications is part of its parent SP 800-53 structure.
- name: SI-4 - System Monitoring
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-4.md
  relation: enhances
  description: SI-4.10 enhances base control SI-4.
nist_id: SI-4.10
sort_id: si-04.10
implementation_level: organization
parameter_ids:
- si-04.10_odp.01
- si-04.10_odp.02
reference_links:
- '#si-4'
---

# Summary

Make provisions so that {{ insert: param, si-04.10_odp.01 }} is visible to {{ insert: param, si-04.10_odp.02 }}.

# Statement

Make provisions so that {{ insert: param, si-04.10_odp.01 }} is visible to {{ insert: param, si-04.10_odp.02 }}.

# Guidance

Organizations balance the need to encrypt communications traffic to protect data confidentiality with the need to maintain visibility into such traffic from a monitoring perspective. Organizations determine whether the visibility requirement applies to internal encrypted traffic, encrypted traffic intended for external destinations, or a subset of the traffic types.

# Parameters

- `si-04.10_odp.01`
- `si-04.10_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
