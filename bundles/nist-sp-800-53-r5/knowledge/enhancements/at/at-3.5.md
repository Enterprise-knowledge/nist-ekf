---
type: control_enhancement
title: AT-3.5 - Processing Personally Identifiable Information
description: 'Provide {{ insert: param, at-03.05_odp.01 }} with initial and {{ insert: param, at-03.05_odp.02 }}
  training in the employment and operation of personally identifiable information processing and transparency controls.'
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
- at
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/at/at-3.md
  relation: part_of
  description: AT-3.5 - Processing Personally Identifiable Information is part of its parent SP 800-53 structure.
- name: AT-3 - Role-based Training
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/at/at-3.md
  relation: enhances
  description: AT-3.5 enhances base control AT-3.
nist_id: AT-3.5
sort_id: at-03.05
implementation_level: organization
parameter_ids:
- at-03.05_odp.01
- at-03.05_odp.02
reference_links:
- '#at-3'
- '#pt-2'
- '#pt-3'
- '#pt-5'
- '#pt-6'
---

# Summary

Provide {{ insert: param, at-03.05_odp.01 }} with initial and {{ insert: param, at-03.05_odp.02 }} training in the employment and operation of personally identifiable information processing and transparency controls.

# Statement

Provide {{ insert: param, at-03.05_odp.01 }} with initial and {{ insert: param, at-03.05_odp.02 }} training in the employment and operation of personally identifiable information processing and transparency controls.

# Guidance

Personally identifiable information processing and transparency controls include the organization’s authority to process personally identifiable information and personally identifiable information processing purposes. Role-based training for federal agencies addresses the types of information that may constitute personally identifiable information and the risks, considerations, and obligations associated with its processing. Such training also considers the authority to process personally identifiable information documented in privacy policies and notices, system of records notices, computer matching agreements and notices, privacy impact assessments, [PRIVACT](#18e71fec-c6fd-475a-925a-5d8495cf8455) statements, contracts, information sharing agreements, memoranda of understanding, and/or other documentation.

# Parameters

- `at-03.05_odp.01`
- `at-03.05_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
