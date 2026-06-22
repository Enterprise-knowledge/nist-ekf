---
type: control_enhancement
title: PE-2.3 - Restrict Unescorted Access
description: 'Restrict unescorted access to the facility where the system resides to personnel with {{ insert: param,
  pe-02.03_odp.01 }}.'
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
- pe
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-2.md
  relation: part_of
  description: PE-2.3 - Restrict Unescorted Access is part of its parent SP 800-53 structure.
- name: PE-2 - Physical Access Authorizations
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-2.md
  relation: enhances
  description: PE-2.3 enhances base control PE-2.
nist_id: PE-2.3
sort_id: pe-02.03
implementation_level: organization
parameter_ids:
- pe-02.03_odp.01
- pe-02.03_odp.02
reference_links:
- '#pe-2'
- '#ps-2'
- '#ps-6'
---

# Summary

Restrict unescorted access to the facility where the system resides to personnel with {{ insert: param, pe-02.03_odp.01 }}.

# Statement

Restrict unescorted access to the facility where the system resides to personnel with {{ insert: param, pe-02.03_odp.01 }}.

# Guidance

Individuals without required security clearances, access approvals, or need to know are escorted by individuals with appropriate physical access authorizations to ensure that information is not exposed or otherwise compromised.

# Parameters

- `pe-02.03_odp.01`
- `pe-02.03_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
