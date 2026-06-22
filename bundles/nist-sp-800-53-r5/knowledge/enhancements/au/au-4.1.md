---
type: control_enhancement
title: AU-4.1 - Transfer to Alternate Storage
description: 'Transfer audit logs {{ insert: param, au-04.01_odp }} to a different system, system component, or
  media other than the system or system component conducting the logging.'
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
- au
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-4.md
  relation: part_of
  description: AU-4.1 - Transfer to Alternate Storage is part of its parent SP 800-53 structure.
- name: AU-4 - Audit Log Storage Capacity
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-4.md
  relation: enhances
  description: AU-4.1 enhances base control AU-4.
nist_id: AU-4.1
sort_id: au-04.01
implementation_level: organization
parameter_ids:
- au-04.01_odp
reference_links:
- '#au-4'
---

# Summary

Transfer audit logs {{ insert: param, au-04.01_odp }} to a different system, system component, or media other than the system or system component conducting the logging.

# Statement

Transfer audit logs {{ insert: param, au-04.01_odp }} to a different system, system component, or media other than the system or system component conducting the logging.

# Guidance

Audit log transfer, also known as off-loading, is a common process in systems with limited audit log storage capacity and thus supports availability of the audit logs. The initial audit log storage is only used in a transitory fashion until the system can communicate with the secondary or alternate system allocated to audit log storage, at which point the audit logs are transferred. Transferring audit logs to alternate storage is similar to [AU-9(2)](#au-9.2) in that audit logs are transferred to a different entity. However, the purpose of selecting [AU-9(2)](#au-9.2) is to protect the confidentiality and integrity of audit records. Organizations can select either control enhancement to obtain the benefit of increased audit log storage capacity and preserving the confidentiality, integrity, and availability of audit records and logs.

# Parameters

- `au-04.01_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
