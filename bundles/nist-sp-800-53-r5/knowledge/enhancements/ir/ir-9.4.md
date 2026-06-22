---
type: control_enhancement
title: IR-9.4 - Exposure to Unauthorized Personnel
description: 'Employ the following controls for personnel exposed to information not within assigned access authorizations:
  {{ insert: param, ir-09.04_odp }}.'
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
  description: IR-9.4 - Exposure to Unauthorized Personnel is part of its parent SP 800-53 structure.
- name: IR-9 - Information Spillage Response
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-9.md
  relation: enhances
  description: IR-9.4 enhances base control IR-9.
nist_id: IR-9.4
sort_id: ir-09.04
implementation_level: organization
parameter_ids:
- ir-09.04_odp
reference_links:
- '#ir-9'
---

# Summary

Employ the following controls for personnel exposed to information not within assigned access authorizations: {{ insert: param, ir-09.04_odp }}.

# Statement

Employ the following controls for personnel exposed to information not within assigned access authorizations: {{ insert: param, ir-09.04_odp }}.

# Guidance

Controls include ensuring that personnel who are exposed to spilled information are made aware of the laws, executive orders, directives, regulations, policies, standards, and guidelines regarding the information and the restrictions imposed based on exposure to such information.

# Parameters

- `ir-09.04_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
