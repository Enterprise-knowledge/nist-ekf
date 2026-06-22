---
type: control_enhancement
title: IA-4.4 - Identify User Status
description: 'Manage individual identifiers by uniquely identifying each individual as {{ insert: param, ia-04.04_odp
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
- ia
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-4.md
  relation: part_of
  description: IA-4.4 - Identify User Status is part of its parent SP 800-53 structure.
- name: IA-4 - Identifier Management
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-4.md
  relation: enhances
  description: IA-4.4 enhances base control IA-4.
nist_id: IA-4.4
sort_id: ia-04.04
implementation_level: organization
parameter_ids:
- ia-04.04_odp
reference_links:
- '#ia-4'
---

# Summary

Manage individual identifiers by uniquely identifying each individual as {{ insert: param, ia-04.04_odp }}.

# Statement

Manage individual identifiers by uniquely identifying each individual as {{ insert: param, ia-04.04_odp }}.

# Guidance

Characteristics that identify the status of individuals include contractors, foreign nationals, and non-organizational users. Identifying the status of individuals by these characteristics provides additional information about the people with whom organizational personnel are communicating. For example, it might be useful for a government employee to know that one of the individuals on an email message is a contractor.

# Parameters

- `ia-04.04_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
