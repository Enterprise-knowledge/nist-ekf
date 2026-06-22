---
type: control_enhancement
title: IA-8.4 - Use of Defined Profiles
description: 'Conform to the following profiles for identity management {{ insert: param, ia-08.04_odp }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-8.md
  relation: part_of
  description: IA-8.4 - Use of Defined Profiles is part of its parent SP 800-53 structure.
- name: IA-8 - Identification and Authentication (Non-organizational Users)
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-8.md
  relation: enhances
  description: IA-8.4 enhances base control IA-8.
nist_id: IA-8.4
sort_id: ia-08.04
implementation_level: system
parameter_ids:
- ia-08.04_odp
reference_links:
- '#ia-8'
---

# Summary

Conform to the following profiles for identity management {{ insert: param, ia-08.04_odp }}.

# Statement

Conform to the following profiles for identity management {{ insert: param, ia-08.04_odp }}.

# Guidance

Organizations define profiles for identity management based on open identity management standards. To ensure that open identity management standards are viable, robust, reliable, sustainable, and interoperable as documented, the Federal Government assesses and scopes the standards and technology implementations against applicable laws, executive orders, directives, policies, regulations, standards, and guidelines.

# Parameters

- `ia-08.04_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
