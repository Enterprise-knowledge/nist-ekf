---
type: control_enhancement
title: IR-4.13 - Behavior Analysis
description: 'Analyze anomalous or suspected adversarial behavior in or related to {{ insert: param, ir-04.13_odp
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
- ir
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-4.md
  relation: part_of
  description: IR-4.13 - Behavior Analysis is part of its parent SP 800-53 structure.
- name: IR-4 - Incident Handling
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-4.md
  relation: enhances
  description: IR-4.13 enhances base control IR-4.
nist_id: IR-4.13
sort_id: ir-04.13
implementation_level: organization
parameter_ids:
- ir-04.13_odp
reference_links:
- '#ir-4'
---

# Summary

Analyze anomalous or suspected adversarial behavior in or related to {{ insert: param, ir-04.13_odp }}.

# Statement

Analyze anomalous or suspected adversarial behavior in or related to {{ insert: param, ir-04.13_odp }}.

# Guidance

If the organization maintains a deception environment, an analysis of behaviors in that environment, including resources targeted by the adversary and timing of the incident or event, can provide insight into adversarial tactics, techniques, and procedures. External to a deception environment, the analysis of anomalous adversarial behavior (e.g., changes in system performance or usage patterns) or suspected behavior (e.g., changes in searches for the location of specific resources) can give the organization such insight.

# Parameters

- `ir-04.13_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
