---
type: control_enhancement
title: MP-6.8 - Remote Purging or Wiping of Information
description: 'Provide the capability to purge or wipe information from {{ insert: param, mp-06.08_odp.01 }} {{ insert:
  param, mp-06.08_odp.02 }}.'
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
- mp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-6.md
  relation: part_of
  description: MP-6.8 - Remote Purging or Wiping of Information is part of its parent SP 800-53 structure.
- name: MP-6 - Media Sanitization
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-6.md
  relation: enhances
  description: MP-6.8 enhances base control MP-6.
nist_id: MP-6.8
sort_id: mp-06.08
implementation_level: organization
parameter_ids:
- mp-06.08_odp.01
- mp-06.08_odp.02
- mp-06.08_odp.03
reference_links:
- '#mp-6'
---

# Summary

Provide the capability to purge or wipe information from {{ insert: param, mp-06.08_odp.01 }} {{ insert: param, mp-06.08_odp.02 }}.

# Statement

Provide the capability to purge or wipe information from {{ insert: param, mp-06.08_odp.01 }} {{ insert: param, mp-06.08_odp.02 }}.

# Guidance

Remote purging or wiping of information protects information on organizational systems and system components if systems or components are obtained by unauthorized individuals. Remote purge or wipe commands require strong authentication to help mitigate the risk of unauthorized individuals purging or wiping the system, component, or device. The purge or wipe function can be implemented in a variety of ways, including by overwriting data or information multiple times or by destroying the key necessary to decrypt encrypted data.

# Parameters

- `mp-06.08_odp.01`
- `mp-06.08_odp.02`
- `mp-06.08_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
