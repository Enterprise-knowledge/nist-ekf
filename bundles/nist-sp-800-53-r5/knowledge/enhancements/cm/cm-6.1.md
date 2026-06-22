---
type: control_enhancement
title: CM-6.1 - Automated Management, Application, and Verification
description: 'Manage, apply, and verify configuration settings for {{ insert: param, cm-06.01_odp.01 }} using {{
  insert: param, cm-6.1_prm_2 }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-6.md
  relation: part_of
  description: CM-6.1 - Automated Management, Application, and Verification is part of its parent SP 800-53 structure.
- name: CM-6 - Configuration Settings
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-6.md
  relation: enhances
  description: CM-6.1 enhances base control CM-6.
nist_id: CM-6.1
sort_id: cm-06.01
implementation_level: organization
parameter_ids:
- cm-6.1_prm_2
- cm-06.01_odp.01
- cm-06.01_odp.02
- cm-06.01_odp.03
- cm-06.01_odp.04
reference_links:
- '#cm-6'
- '#ca-7'
---

# Summary

Manage, apply, and verify configuration settings for {{ insert: param, cm-06.01_odp.01 }} using {{ insert: param, cm-6.1_prm_2 }}.

# Statement

Manage, apply, and verify configuration settings for {{ insert: param, cm-06.01_odp.01 }} using {{ insert: param, cm-6.1_prm_2 }}.

# Guidance

Automated tools (e.g., hardening tools, baseline configuration tools) can improve the accuracy, consistency, and availability of configuration settings information. Automation can also provide data aggregation and data correlation capabilities, alerting mechanisms, and dashboards to support risk-based decision-making within the organization.

# Parameters

- `cm-6.1_prm_2`
- `cm-06.01_odp.01`
- `cm-06.01_odp.02`
- `cm-06.01_odp.03`
- `cm-06.01_odp.04`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
