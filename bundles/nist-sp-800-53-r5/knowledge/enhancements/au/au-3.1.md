---
type: control_enhancement
title: AU-3.1 - Additional Audit Information
description: 'Generate audit records containing the following additional information: {{ insert: param, au-03.01_odp
  }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-3.md
  relation: part_of
  description: AU-3.1 - Additional Audit Information is part of its parent SP 800-53 structure.
- name: AU-3 - Content of Audit Records
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-3.md
  relation: enhances
  description: AU-3.1 enhances base control AU-3.
nist_id: AU-3.1
sort_id: au-03.01
implementation_level: system
parameter_ids:
- au-03.01_odp
reference_links:
- '#au-3'
---

# Summary

Generate audit records containing the following additional information: {{ insert: param, au-03.01_odp }}.

# Statement

Generate audit records containing the following additional information: {{ insert: param, au-03.01_odp }}.

# Guidance

The ability to add information generated in audit records is dependent on system functionality to configure the audit record content. Organizations may consider additional information in audit records including, but not limited to, access control or flow control rules invoked and individual identities of group account users. Organizations may also consider limiting additional audit record information to only information that is explicitly needed for audit requirements. This facilitates the use of audit trails and audit logs by not including information in audit records that could potentially be misleading, make it more difficult to locate information of interest, or increase the risk to individuals' privacy.

# Parameters

- `au-03.01_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
