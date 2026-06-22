---
type: control_enhancement
title: IA-5.8 - Multiple System Accounts
description: 'Implement {{ insert: param, ia-05.08_odp }} to manage the risk of compromise due to individuals having
  accounts on multiple systems.'
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
- ia
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-5.md
  relation: part_of
  description: IA-5.8 - Multiple System Accounts is part of its parent SP 800-53 structure.
- name: IA-5 - Authenticator Management
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-5.md
  relation: enhances
  description: IA-5.8 enhances base control IA-5.
nist_id: IA-5.8
sort_id: ia-05.08
implementation_level: organization
parameter_ids:
- ia-05.08_odp
reference_links:
- '#ia-5'
- '#ps-6'
---

# Summary

Implement {{ insert: param, ia-05.08_odp }} to manage the risk of compromise due to individuals having accounts on multiple systems.

# Statement

Implement {{ insert: param, ia-05.08_odp }} to manage the risk of compromise due to individuals having accounts on multiple systems.

# Guidance

When individuals have accounts on multiple systems and use the same authenticators such as passwords, there is the risk that a compromise of one account may lead to the compromise of other accounts. Alternative approaches include having different authenticators (passwords) on all systems, employing a single sign-on or federation mechanism, or using some form of one-time passwords on all systems. Organizations can also use rules of behavior (see [PL-4](#pl-4) ) and access agreements (see [PS-6](#ps-6) ) to mitigate the risk of multiple system accounts.

# Parameters

- `ia-05.08_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
