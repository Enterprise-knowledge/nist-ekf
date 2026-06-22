---
type: control_enhancement
title: CP-4.3 - Automated Testing
description: 'Test the contingency plan using {{ insert: param, cp-04.03_odp }}.'
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
  description: CP-4.3 - Automated Testing is part of its parent SP 800-53 structure.
- name: CP-4 - Contingency Plan Testing
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-4.md
  relation: enhances
  description: CP-4.3 enhances base control CP-4.
nist_id: CP-4.3
sort_id: cp-04.03
implementation_level: organization
parameter_ids:
- cp-04.03_odp
reference_links:
- '#cp-4'
---

# Summary

Test the contingency plan using {{ insert: param, cp-04.03_odp }}.

# Statement

Test the contingency plan using {{ insert: param, cp-04.03_odp }}.

# Guidance

Automated mechanisms facilitate thorough and effective testing of contingency plans by providing more complete coverage of contingency issues, selecting more realistic test scenarios and environments, and effectively stressing the system and supported mission and business functions.

# Parameters

- `cp-04.03_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
