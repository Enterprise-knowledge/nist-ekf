---
type: control_enhancement
title: IR-2.2 - Automated Training Environments
description: 'Provide an incident response training environment using {{ insert: param, ir-02.02_odp }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-2.md
  relation: part_of
  description: IR-2.2 - Automated Training Environments is part of its parent SP 800-53 structure.
- name: IR-2 - Incident Response Training
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-2.md
  relation: enhances
  description: IR-2.2 enhances base control IR-2.
nist_id: IR-2.2
sort_id: ir-02.02
implementation_level: organization
parameter_ids:
- ir-02.02_odp
reference_links:
- '#ir-2'
---

# Summary

Provide an incident response training environment using {{ insert: param, ir-02.02_odp }}.

# Statement

Provide an incident response training environment using {{ insert: param, ir-02.02_odp }}.

# Guidance

Automated mechanisms can provide a more thorough and realistic incident response training environment. This can be accomplished, for example, by providing more complete coverage of incident response issues, selecting more realistic training scenarios and environments, and stressing the response capability.

# Parameters

- `ir-02.02_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
