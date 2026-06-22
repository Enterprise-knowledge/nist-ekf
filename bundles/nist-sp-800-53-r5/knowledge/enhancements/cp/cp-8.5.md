---
type: control_enhancement
title: CP-8.5 - Alternate Telecommunication Service Testing
description: 'Test alternate telecommunication services {{ insert: param, cp-08.05_odp }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-8.md
  relation: part_of
  description: CP-8.5 - Alternate Telecommunication Service Testing is part of its parent SP 800-53 structure.
- name: CP-8 - Telecommunications Services
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-8.md
  relation: enhances
  description: CP-8.5 enhances base control CP-8.
nist_id: CP-8.5
sort_id: cp-08.05
implementation_level: organization
parameter_ids:
- cp-08.05_odp
reference_links:
- '#cp-8'
- '#cp-3'
---

# Summary

Test alternate telecommunication services {{ insert: param, cp-08.05_odp }}.

# Statement

Test alternate telecommunication services {{ insert: param, cp-08.05_odp }}.

# Guidance

Alternate telecommunications services testing is arranged through contractual agreements with service providers. The testing may occur in parallel with normal operations to ensure that there is no degradation in organizational missions or functions.

# Parameters

- `cp-08.05_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
