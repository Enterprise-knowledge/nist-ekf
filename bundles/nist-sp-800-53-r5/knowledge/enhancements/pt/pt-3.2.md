---
type: control_enhancement
title: PT-3.2 - Automation
description: 'Track processing purposes of personally identifiable information using {{ insert: param, pt-03.02_odp
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
- pt
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-3.md
  relation: part_of
  description: PT-3.2 - Automation is part of its parent SP 800-53 structure.
- name: PT-3 - Personally Identifiable Information Processing Purposes
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-3.md
  relation: enhances
  description: PT-3.2 enhances base control PT-3.
nist_id: PT-3.2
sort_id: pt-03.02
implementation_level: organization
parameter_ids:
- pt-03.02_odp
reference_links:
- '#pt-3'
- '#ca-6'
- '#cm-12'
- '#pm-5'
- '#pm-22'
- '#sc-16'
- '#sc-43'
- '#si-10'
- '#si-15'
- '#si-19'
---

# Summary

Track processing purposes of personally identifiable information using {{ insert: param, pt-03.02_odp }}.

# Statement

Track processing purposes of personally identifiable information using {{ insert: param, pt-03.02_odp }}.

# Guidance

Automated mechanisms augment tracking of the processing purposes.

# Parameters

- `pt-03.02_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
