---
type: control_enhancement
title: AU-5.3 - Configurable Traffic Volume Thresholds
description: 'Enforce configurable network communications traffic volume thresholds reflecting limits on audit log
  storage capacity and {{ insert: param, au-05.03_odp }} network traffic above those thresholds.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-5.md
  relation: part_of
  description: AU-5.3 - Configurable Traffic Volume Thresholds is part of its parent SP 800-53 structure.
- name: AU-5 - Response to Audit Logging Process Failures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-5.md
  relation: enhances
  description: AU-5.3 enhances base control AU-5.
nist_id: AU-5.3
sort_id: au-05.03
implementation_level: system
parameter_ids:
- au-05.03_odp
reference_links:
- '#au-5'
---

# Summary

Enforce configurable network communications traffic volume thresholds reflecting limits on audit log storage capacity and {{ insert: param, au-05.03_odp }} network traffic above those thresholds.

# Statement

Enforce configurable network communications traffic volume thresholds reflecting limits on audit log storage capacity and {{ insert: param, au-05.03_odp }} network traffic above those thresholds.

# Guidance

Organizations have the capability to reject or delay the processing of network communications traffic if audit logging information about such traffic is determined to exceed the storage capacity of the system audit logging function. The rejection or delay response is triggered by the established organizational traffic volume thresholds that can be adjusted based on changes to audit log storage capacity.

# Parameters

- `au-05.03_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
