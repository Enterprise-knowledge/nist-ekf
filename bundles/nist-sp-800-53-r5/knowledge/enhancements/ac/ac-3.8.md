---
type: control_enhancement
title: AC-3.8 - Revocation of Access Authorizations
description: 'Enforce the revocation of access authorizations resulting from changes to the security attributes
  of subjects and objects based on {{ insert: param, ac-03.08_odp }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-3.md
  relation: part_of
  description: AC-3.8 - Revocation of Access Authorizations is part of its parent SP 800-53 structure.
- name: AC-3 - Access Enforcement
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-3.md
  relation: enhances
  description: AC-3.8 enhances base control AC-3.
nist_id: AC-3.8
sort_id: ac-03.08
implementation_level: organization
parameter_ids:
- ac-03.08_odp
reference_links:
- '#ac-3'
---

# Summary

Enforce the revocation of access authorizations resulting from changes to the security attributes of subjects and objects based on {{ insert: param, ac-03.08_odp }}.

# Statement

Enforce the revocation of access authorizations resulting from changes to the security attributes of subjects and objects based on {{ insert: param, ac-03.08_odp }}.

# Guidance

Revocation of access rules may differ based on the types of access revoked. For example, if a subject (i.e., user or process acting on behalf of a user) is removed from a group, access may not be revoked until the next time the object is opened or the next time the subject attempts to access the object. Revocation based on changes to security labels may take effect immediately. Organizations provide alternative approaches on how to make revocations immediate if systems cannot provide such capability and immediate revocation is necessary.

# Parameters

- `ac-03.08_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
