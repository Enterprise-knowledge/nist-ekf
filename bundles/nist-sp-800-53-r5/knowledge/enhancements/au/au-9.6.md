---
type: control_enhancement
title: AU-9.6 - Read-only Access
description: 'Authorize read-only access to audit information to {{ insert: param, au-09.06_odp }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-9.md
  relation: part_of
  description: AU-9.6 - Read-only Access is part of its parent SP 800-53 structure.
- name: AU-9 - Protection of Audit Information
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-9.md
  relation: enhances
  description: AU-9.6 enhances base control AU-9.
nist_id: AU-9.6
sort_id: au-09.06
implementation_level: organization
parameter_ids:
- au-09.06_odp
reference_links:
- '#au-9'
---

# Summary

Authorize read-only access to audit information to {{ insert: param, au-09.06_odp }}.

# Statement

Authorize read-only access to audit information to {{ insert: param, au-09.06_odp }}.

# Guidance

Restricting privileged user or role authorizations to read-only helps to limit the potential damage to organizations that could be initiated by such users or roles, such as deleting audit records to cover up malicious activity.

# Parameters

- `au-09.06_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
