---
type: control_enhancement
title: CM-6.2 - Respond to Unauthorized Changes
description: 'Take the following actions in response to unauthorized changes to {{ insert: param, cm-06.02_odp.02
  }}: {{ insert: param, cm-06.02_odp.01 }}.'
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
  description: CM-6.2 - Respond to Unauthorized Changes is part of its parent SP 800-53 structure.
- name: CM-6 - Configuration Settings
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-6.md
  relation: enhances
  description: CM-6.2 enhances base control CM-6.
nist_id: CM-6.2
sort_id: cm-06.02
implementation_level: organization
parameter_ids:
- cm-06.02_odp.01
- cm-06.02_odp.02
reference_links:
- '#cm-6'
- '#ir-4'
- '#ir-6'
- '#si-7'
---

# Summary

Take the following actions in response to unauthorized changes to {{ insert: param, cm-06.02_odp.02 }}: {{ insert: param, cm-06.02_odp.01 }}.

# Statement

Take the following actions in response to unauthorized changes to {{ insert: param, cm-06.02_odp.02 }}: {{ insert: param, cm-06.02_odp.01 }}.

# Guidance

Responses to unauthorized changes to configuration settings include alerting designated organizational personnel, restoring established configuration settings, or—in extreme cases—halting affected system processing.

# Parameters

- `cm-06.02_odp.01`
- `cm-06.02_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
