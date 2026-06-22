---
type: control_enhancement
title: CP-6.2 - Recovery Time and Recovery Point Objectives
description: Configure the alternate storage site to facilitate recovery operations in accordance with recovery
  time and recovery point objectives.
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
- cp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-6.md
  relation: part_of
  description: CP-6.2 - Recovery Time and Recovery Point Objectives is part of its parent SP 800-53 structure.
- name: CP-6 - Alternate Storage Site
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-6.md
  relation: enhances
  description: CP-6.2 enhances base control CP-6.
nist_id: CP-6.2
sort_id: cp-06.02
implementation_level: organization
parameter_ids: []
reference_links:
- '#cp-6'
---

# Summary

Configure the alternate storage site to facilitate recovery operations in accordance with recovery time and recovery point objectives.

# Statement

Configure the alternate storage site to facilitate recovery operations in accordance with recovery time and recovery point objectives.

# Guidance

Organizations establish recovery time and recovery point objectives as part of contingency planning. Configuration of the alternate storage site includes physical facilities and the systems supporting recovery operations that ensure accessibility and correct execution.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
