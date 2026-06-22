---
type: control_enhancement
title: PE-8.3 - Limit Personally Identifiable Information Elements
description: 'Limit personally identifiable information contained in visitor access records to the following elements
  identified in the privacy risk assessment: {{ insert: param, pe-08.03_odp }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-8.md
  relation: part_of
  description: PE-8.3 - Limit Personally Identifiable Information Elements is part of its parent SP 800-53 structure.
- name: PE-8 - Visitor Access Records
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-8.md
  relation: enhances
  description: PE-8.3 enhances base control PE-8.
nist_id: PE-8.3
sort_id: pe-08.03
implementation_level: organization
parameter_ids:
- pe-08.03_odp
reference_links:
- '#pe-8'
- '#ra-3'
- '#sa-8'
---

# Summary

Limit personally identifiable information contained in visitor access records to the following elements identified in the privacy risk assessment: {{ insert: param, pe-08.03_odp }}.

# Statement

Limit personally identifiable information contained in visitor access records to the following elements identified in the privacy risk assessment: {{ insert: param, pe-08.03_odp }}.

# Guidance

Organizations may have requirements that specify the contents of visitor access records. Limiting personally identifiable information in visitor access records when such information is not needed for operational purposes helps reduce the level of privacy risk created by a system.

# Parameters

- `pe-08.03_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
