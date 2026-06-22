---
type: control_enhancement
title: SI-4.21 - Probationary Periods
description: 'Implement the following additional monitoring of individuals during {{ insert: param, si-04.21_odp.02
  }}: {{ insert: param, si-04.21_odp.01 }}.'
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
- si
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-4.md
  relation: part_of
  description: SI-4.21 - Probationary Periods is part of its parent SP 800-53 structure.
- name: SI-4 - System Monitoring
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-4.md
  relation: enhances
  description: SI-4.21 enhances base control SI-4.
nist_id: SI-4.21
sort_id: si-04.21
implementation_level: organization
parameter_ids:
- si-04.21_odp.01
- si-04.21_odp.02
reference_links:
- '#si-4'
- '#ac-18'
---

# Summary

Implement the following additional monitoring of individuals during {{ insert: param, si-04.21_odp.02 }}: {{ insert: param, si-04.21_odp.01 }}.

# Statement

Implement the following additional monitoring of individuals during {{ insert: param, si-04.21_odp.02 }}: {{ insert: param, si-04.21_odp.01 }}.

# Guidance

During probationary periods, employees do not have permanent employment status within organizations. Without such status or access to information that is resident on the system, additional monitoring can help identify any potentially malicious activity or inappropriate behavior.

# Parameters

- `si-04.21_odp.01`
- `si-04.21_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
