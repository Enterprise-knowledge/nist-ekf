---
type: control_enhancement
title: PE-2.2 - Two Forms of Identification
description: 'Require two forms of identification from the following forms of identification for visitor access
  to the facility where the system resides: {{ insert: param, pe-02.02_odp }}.'
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
- pe
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-2.md
  relation: part_of
  description: PE-2.2 - Two Forms of Identification is part of its parent SP 800-53 structure.
- name: PE-2 - Physical Access Authorizations
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-2.md
  relation: enhances
  description: PE-2.2 enhances base control PE-2.
nist_id: PE-2.2
sort_id: pe-02.02
implementation_level: organization
parameter_ids:
- pe-02.02_odp
reference_links:
- '#pe-2'
- '#ia-2'
- '#ia-4'
- '#ia-5'
---

# Summary

Require two forms of identification from the following forms of identification for visitor access to the facility where the system resides: {{ insert: param, pe-02.02_odp }}.

# Statement

Require two forms of identification from the following forms of identification for visitor access to the facility where the system resides: {{ insert: param, pe-02.02_odp }}.

# Guidance

Acceptable forms of identification include passports, REAL ID-compliant drivers’ licenses, and Personal Identity Verification (PIV) cards. For gaining access to facilities using automated mechanisms, organizations may use PIV cards, key cards, PINs, and biometrics.

# Parameters

- `pe-02.02_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
