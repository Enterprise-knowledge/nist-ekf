---
type: control_enhancement
title: AC-2.8 - Dynamic Account Management
description: 'Create, activate, manage, and deactivate {{ insert: param, ac-02.08_odp }} dynamically.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-2.md
  relation: part_of
  description: AC-2.8 - Dynamic Account Management is part of its parent SP 800-53 structure.
- name: AC-2 - Account Management
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-2.md
  relation: enhances
  description: AC-2.8 enhances base control AC-2.
nist_id: AC-2.8
sort_id: ac-02.08
implementation_level: system
parameter_ids:
- ac-02.08_odp
reference_links:
- '#ac-2'
- '#ac-16'
---

# Summary

Create, activate, manage, and deactivate {{ insert: param, ac-02.08_odp }} dynamically.

# Statement

Create, activate, manage, and deactivate {{ insert: param, ac-02.08_odp }} dynamically.

# Guidance

Approaches for dynamically creating, activating, managing, and deactivating system accounts rely on automatically provisioning the accounts at runtime for entities that were previously unknown. Organizations plan for the dynamic management, creation, activation, and deactivation of system accounts by establishing trust relationships, business rules, and mechanisms with appropriate authorities to validate related authorizations and privileges.

# Parameters

- `ac-02.08_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
