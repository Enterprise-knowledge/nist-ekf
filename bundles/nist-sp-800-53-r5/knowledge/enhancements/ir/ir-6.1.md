---
type: control_enhancement
title: IR-6.1 - Automated Reporting
description: 'Report incidents using {{ insert: param, ir-06.01_odp }}.'
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
- ir
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-6.md
  relation: part_of
  description: IR-6.1 - Automated Reporting is part of its parent SP 800-53 structure.
- name: IR-6 - Incident Reporting
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-6.md
  relation: enhances
  description: IR-6.1 enhances base control IR-6.
nist_id: IR-6.1
sort_id: ir-06.01
implementation_level: organization
parameter_ids:
- ir-06.01_odp
reference_links:
- '#ir-6'
- '#ir-7'
---

# Summary

Report incidents using {{ insert: param, ir-06.01_odp }}.

# Statement

Report incidents using {{ insert: param, ir-06.01_odp }}.

# Guidance

The recipients of incident reports are specified in [IR-6b](#ir-6_smt.b) . Automated reporting mechanisms include email, posting on websites (with automatic updates), and automated incident response tools and programs.

# Parameters

- `ir-06.01_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
