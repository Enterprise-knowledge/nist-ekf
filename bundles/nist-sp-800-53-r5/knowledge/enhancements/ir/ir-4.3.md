---
type: control_enhancement
title: IR-4.3 - Continuity of Operations
description: 'Identify {{ insert: param, ir-04.03_odp.01 }} and take the following actions in response to those
  incidents to ensure continuation of organizational mission and business functions: {{ insert: param, ir-04.03_odp.02
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
  description: IR-4.3 - Continuity of Operations is part of its parent SP 800-53 structure.
- name: IR-4 - Incident Handling
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-4.md
  relation: enhances
  description: IR-4.3 enhances base control IR-4.
nist_id: IR-4.3
sort_id: ir-04.03
implementation_level: organization
parameter_ids:
- ir-04.03_odp.01
- ir-04.03_odp.02
reference_links:
- '#ir-4'
---

# Summary

Identify {{ insert: param, ir-04.03_odp.01 }} and take the following actions in response to those incidents to ensure continuation of organizational mission and business functions: {{ insert: param, ir-04.03_odp.02 }}.

# Statement

Identify {{ insert: param, ir-04.03_odp.01 }} and take the following actions in response to those incidents to ensure continuation of organizational mission and business functions: {{ insert: param, ir-04.03_odp.02 }}.

# Guidance

Classes of incidents include malfunctions due to design or implementation errors and omissions, targeted malicious attacks, and untargeted malicious attacks. Incident response actions include orderly system degradation, system shutdown, fall back to manual mode or activation of alternative technology whereby the system operates differently, employing deceptive measures, alternate information flows, or operating in a mode that is reserved for when systems are under attack. Organizations consider whether continuity of operations requirements during an incident conflict with the capability to automatically disable the system as specified as part of [IR-4(5)](#ir-4.5).

# Parameters

- `ir-04.03_odp.01`
- `ir-04.03_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
