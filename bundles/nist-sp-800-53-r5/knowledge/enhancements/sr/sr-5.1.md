---
type: control_enhancement
title: SR-5.1 - Adequate Supply
description: 'Employ the following controls to ensure an adequate supply of {{ insert: param, sr-05.01_odp.02 }}:
  {{ insert: param, sr-05.01_odp.01 }}.'
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
- sr
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-5.md
  relation: part_of
  description: SR-5.1 - Adequate Supply is part of its parent SP 800-53 structure.
- name: SR-5 - Acquisition Strategies, Tools, and Methods
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-5.md
  relation: enhances
  description: SR-5.1 enhances base control SR-5.
nist_id: SR-5.1
sort_id: sr-05.01
implementation_level: organization
parameter_ids:
- sr-05.01_odp.01
- sr-05.01_odp.02
reference_links:
- '#sr-5'
- '#ra-9'
---

# Summary

Employ the following controls to ensure an adequate supply of {{ insert: param, sr-05.01_odp.02 }}: {{ insert: param, sr-05.01_odp.01 }}.

# Statement

Employ the following controls to ensure an adequate supply of {{ insert: param, sr-05.01_odp.02 }}: {{ insert: param, sr-05.01_odp.01 }}.

# Guidance

Adversaries can attempt to impede organizational operations by disrupting the supply of critical system components or corrupting supplier operations. Organizations may track systems and component mean time to failure to mitigate the loss of temporary or permanent system function. Controls to ensure that adequate supplies of critical system components include the use of multiple suppliers throughout the supply chain for the identified critical components, stockpiling spare components to ensure operation during mission-critical times, and the identification of functionally identical or similar components that may be used, if necessary.

# Parameters

- `sr-05.01_odp.01`
- `sr-05.01_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
