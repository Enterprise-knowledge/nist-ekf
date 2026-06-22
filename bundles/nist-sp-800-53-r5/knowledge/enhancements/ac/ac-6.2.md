---
type: control_enhancement
title: AC-6.2 - Non-privileged Access for Nonsecurity Functions
description: 'Require that users of system accounts (or roles) with access to {{ insert: param, ac-06.02_odp }}
  use non-privileged accounts or roles, when accessing nonsecurity functions.'
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
- ac
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-6.md
  relation: part_of
  description: AC-6.2 - Non-privileged Access for Nonsecurity Functions is part of its parent SP 800-53 structure.
- name: AC-6 - Least Privilege
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-6.md
  relation: enhances
  description: AC-6.2 enhances base control AC-6.
nist_id: AC-6.2
sort_id: ac-06.02
implementation_level: organization
parameter_ids:
- ac-06.02_odp
reference_links:
- '#ac-6'
- '#ac-17'
- '#ac-18'
- '#ac-19'
- '#pl-4'
---

# Summary

Require that users of system accounts (or roles) with access to {{ insert: param, ac-06.02_odp }} use non-privileged accounts or roles, when accessing nonsecurity functions.

# Statement

Require that users of system accounts (or roles) with access to {{ insert: param, ac-06.02_odp }} use non-privileged accounts or roles, when accessing nonsecurity functions.

# Guidance

Requiring the use of non-privileged accounts when accessing nonsecurity functions limits exposure when operating from within privileged accounts or roles. The inclusion of roles addresses situations where organizations implement access control policies, such as role-based access control, and where a change of role provides the same degree of assurance in the change of access authorizations for the user and the processes acting on behalf of the user as would be provided by a change between a privileged and non-privileged account.

# Parameters

- `ac-06.02_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
