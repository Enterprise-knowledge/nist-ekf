---
type: control_enhancement
title: IA-4.9 - Attribute Maintenance and Protection
description: 'Maintain the attributes for each uniquely identified individual, device, or service in {{ insert:
  param, ia-04.09_odp }}.'
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
  description: IA-4.9 - Attribute Maintenance and Protection is part of its parent SP 800-53 structure.
- name: IA-4 - Identifier Management
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-4.md
  relation: enhances
  description: IA-4.9 enhances base control IA-4.
nist_id: IA-4.9
sort_id: ia-04.09
implementation_level: organization
parameter_ids:
- ia-04.09_odp
reference_links:
- '#ia-4'
---

# Summary

Maintain the attributes for each uniquely identified individual, device, or service in {{ insert: param, ia-04.09_odp }}.

# Statement

Maintain the attributes for each uniquely identified individual, device, or service in {{ insert: param, ia-04.09_odp }}.

# Guidance

For each of the entities covered in [IA-2](#ia-2), [IA-3](#ia-3), [IA-8](#ia-8) , and [IA-9](#ia-9) , it is important to maintain the attributes for each authenticated entity on an ongoing basis in a central (protected) store.

# Parameters

- `ia-04.09_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
