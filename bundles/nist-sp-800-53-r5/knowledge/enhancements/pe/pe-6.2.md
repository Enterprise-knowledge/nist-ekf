---
type: control_enhancement
title: PE-6.2 - Automated Intrusion Recognition and Responses
description: 'Recognize {{ insert: param, pe-06.02_odp.01 }} and initiate {{ insert: param, pe-06.02_odp.02 }} using
  {{ insert: param, pe-06.02_odp.03 }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-6.md
  relation: part_of
  description: PE-6.2 - Automated Intrusion Recognition and Responses is part of its parent SP 800-53 structure.
- name: PE-6 - Monitoring Physical Access
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-6.md
  relation: enhances
  description: PE-6.2 enhances base control PE-6.
nist_id: PE-6.2
sort_id: pe-06.02
implementation_level: organization
parameter_ids:
- pe-06.02_odp.01
- pe-06.02_odp.02
- pe-06.02_odp.03
reference_links:
- '#pe-6'
- '#si-4'
---

# Summary

Recognize {{ insert: param, pe-06.02_odp.01 }} and initiate {{ insert: param, pe-06.02_odp.02 }} using {{ insert: param, pe-06.02_odp.03 }}.

# Statement

Recognize {{ insert: param, pe-06.02_odp.01 }} and initiate {{ insert: param, pe-06.02_odp.02 }} using {{ insert: param, pe-06.02_odp.03 }}.

# Guidance

Response actions can include notifying selected organizational personnel or law enforcement personnel. Automated mechanisms implemented to initiate response actions include system alert notifications, email and text messages, and activating door locking mechanisms. Physical access monitoring can be coordinated with intrusion detection systems and system monitoring capabilities to provide integrated threat coverage for the organization.

# Parameters

- `pe-06.02_odp.01`
- `pe-06.02_odp.02`
- `pe-06.02_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
