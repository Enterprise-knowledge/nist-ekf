---
type: control_enhancement
title: IR-5.1 - Automated Tracking, Data Collection, and Analysis
description: 'Track incidents and collect and analyze incident information using {{ insert: param, ir-5.1_prm_1
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-5.md
  relation: part_of
  description: IR-5.1 - Automated Tracking, Data Collection, and Analysis is part of its parent SP 800-53 structure.
- name: IR-5 - Incident Monitoring
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-5.md
  relation: enhances
  description: IR-5.1 enhances base control IR-5.
nist_id: IR-5.1
sort_id: ir-05.01
implementation_level: organization
parameter_ids:
- ir-5.1_prm_1
- ir-05.01_odp.01
- ir-05.01_odp.02
- ir-05.01_odp.03
reference_links:
- '#ir-5'
---

# Summary

Track incidents and collect and analyze incident information using {{ insert: param, ir-5.1_prm_1 }}.

# Statement

Track incidents and collect and analyze incident information using {{ insert: param, ir-5.1_prm_1 }}.

# Guidance

Automated mechanisms for tracking incidents and collecting and analyzing incident information include Computer Incident Response Centers or other electronic databases of incidents and network monitoring devices.

# Parameters

- `ir-5.1_prm_1`
- `ir-05.01_odp.01`
- `ir-05.01_odp.02`
- `ir-05.01_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
