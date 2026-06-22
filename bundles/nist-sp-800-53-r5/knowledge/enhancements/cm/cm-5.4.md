---
type: control_enhancement
title: CM-5.4 - Dual Authorization
description: 'Enforce dual authorization for implementing changes to {{ insert: param, cm-5.4_prm_1 }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-5.md
  relation: part_of
  description: CM-5.4 - Dual Authorization is part of its parent SP 800-53 structure.
- name: CM-5 - Access Restrictions for Change
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-5.md
  relation: enhances
  description: CM-5.4 enhances base control CM-5.
nist_id: CM-5.4
sort_id: cm-05.04
implementation_level: organization
parameter_ids:
- cm-5.4_prm_1
- cm-05.04_odp.01
- cm-05.04_odp.02
reference_links:
- '#cm-5'
- '#ac-2'
- '#ac-5'
- '#cm-3'
---

# Summary

Enforce dual authorization for implementing changes to {{ insert: param, cm-5.4_prm_1 }}.

# Statement

Enforce dual authorization for implementing changes to {{ insert: param, cm-5.4_prm_1 }}.

# Guidance

Organizations employ dual authorization to help ensure that any changes to selected system components and information cannot occur unless two qualified individuals approve and implement such changes. The two individuals possess the skills and expertise to determine if the proposed changes are correct implementations of approved changes. The individuals are also accountable for the changes. Dual authorization may also be known as two-person control. To reduce the risk of collusion, organizations consider rotating dual authorization duties to other individuals. System-level information includes operational procedures.

# Parameters

- `cm-5.4_prm_1`
- `cm-05.04_odp.01`
- `cm-05.04_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
