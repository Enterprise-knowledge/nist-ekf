---
type: control_enhancement
title: CM-3.4 - Security and Privacy Representatives
description: 'Require {{ insert: param, cm-3.4_prm_1 }} to be members of the {{ insert: param, cm-03.04_odp.03 }}.'
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
- cm
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-3.md
  relation: part_of
  description: CM-3.4 - Security and Privacy Representatives is part of its parent SP 800-53 structure.
- name: CM-3 - Configuration Change Control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-3.md
  relation: enhances
  description: CM-3.4 enhances base control CM-3.
nist_id: CM-3.4
sort_id: cm-03.04
implementation_level: organization
parameter_ids:
- cm-3.4_prm_1
- cm-03.04_odp.01
- cm-03.04_odp.02
- cm-03.04_odp.03
reference_links:
- '#cm-3'
---

# Summary

Require {{ insert: param, cm-3.4_prm_1 }} to be members of the {{ insert: param, cm-03.04_odp.03 }}.

# Statement

Require {{ insert: param, cm-3.4_prm_1 }} to be members of the {{ insert: param, cm-03.04_odp.03 }}.

# Guidance

Information security and privacy representatives include system security officers, senior agency information security officers, senior agency officials for privacy, or system privacy officers. Representation by personnel with information security and privacy expertise is important because changes to system configurations can have unintended side effects, some of which may be security- or privacy-relevant. Detecting such changes early in the process can help avoid unintended, negative consequences that could ultimately affect the security and privacy posture of systems. The configuration change control element referred to in the second organization-defined parameter reflects the change control elements defined by organizations in [CM-3g](#cm-3_smt.g).

# Parameters

- `cm-3.4_prm_1`
- `cm-03.04_odp.01`
- `cm-03.04_odp.02`
- `cm-03.04_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
