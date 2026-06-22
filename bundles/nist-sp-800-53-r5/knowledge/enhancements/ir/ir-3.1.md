---
type: control_enhancement
title: IR-3.1 - Automated Testing
description: 'Test the incident response capability using {{ insert: param, ir-03.01_odp }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-3.md
  relation: part_of
  description: IR-3.1 - Automated Testing is part of its parent SP 800-53 structure.
- name: IR-3 - Incident Response Testing
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-3.md
  relation: enhances
  description: IR-3.1 enhances base control IR-3.
nist_id: IR-3.1
sort_id: ir-03.01
implementation_level: organization
parameter_ids:
- ir-03.01_odp
reference_links:
- '#ir-3'
---

# Summary

Test the incident response capability using {{ insert: param, ir-03.01_odp }}.

# Statement

Test the incident response capability using {{ insert: param, ir-03.01_odp }}.

# Guidance

Organizations use automated mechanisms to more thoroughly and effectively test incident response capabilities. This can be accomplished by providing more complete coverage of incident response issues, selecting realistic test scenarios and environments, and stressing the response capability.

# Parameters

- `ir-03.01_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
