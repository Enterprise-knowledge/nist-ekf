---
type: control_enhancement
title: CP-4.5 - Self-challenge
description: 'Employ {{ insert: param, cp-04.05_odp.01 }} to {{ insert: param, cp-04.05_odp.02 }} to disrupt and
  adversely affect the system or system component.'
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
- cp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-4.md
  relation: part_of
  description: CP-4.5 - Self-challenge is part of its parent SP 800-53 structure.
- name: CP-4 - Contingency Plan Testing
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-4.md
  relation: enhances
  description: CP-4.5 enhances base control CP-4.
nist_id: CP-4.5
sort_id: cp-04.05
implementation_level: organization
parameter_ids:
- cp-04.05_odp.01
- cp-04.05_odp.02
reference_links:
- '#cp-4'
---

# Summary

Employ {{ insert: param, cp-04.05_odp.01 }} to {{ insert: param, cp-04.05_odp.02 }} to disrupt and adversely affect the system or system component.

# Statement

Employ {{ insert: param, cp-04.05_odp.01 }} to {{ insert: param, cp-04.05_odp.02 }} to disrupt and adversely affect the system or system component.

# Guidance

Often, the best method of assessing system resilience is to disrupt the system in some manner. The mechanisms used by the organization could disrupt system functions or system services in many ways, including terminating or disabling critical system components, changing the configuration of system components, degrading critical functionality (e.g., restricting network bandwidth), or altering privileges. Automated, on-going, and simulated cyber-attacks and service disruptions can reveal unexpected functional dependencies and help the organization determine its ability to ensure resilience in the face of an actual cyber-attack.

# Parameters

- `cp-04.05_odp.01`
- `cp-04.05_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
