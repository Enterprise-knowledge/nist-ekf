---
type: control_enhancement
title: IR-9.2 - Training
description: 'Provide information spillage response training {{ insert: param, ir-09.02_odp }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-9.md
  relation: part_of
  description: IR-9.2 - Training is part of its parent SP 800-53 structure.
- name: IR-9 - Information Spillage Response
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-9.md
  relation: enhances
  description: IR-9.2 enhances base control IR-9.
nist_id: IR-9.2
sort_id: ir-09.02
implementation_level: organization
parameter_ids:
- ir-09.02_odp
reference_links:
- '#ir-9'
- '#at-2'
- '#at-3'
- '#cp-3'
- '#ir-2'
---

# Summary

Provide information spillage response training {{ insert: param, ir-09.02_odp }}.

# Statement

Provide information spillage response training {{ insert: param, ir-09.02_odp }}.

# Guidance

Organizations establish requirements for responding to information spillage incidents in incident response plans. Incident response training on a regular basis helps to ensure that organizational personnel understand their individual responsibilities and what specific actions to take when spillage incidents occur.

# Parameters

- `ir-09.02_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
