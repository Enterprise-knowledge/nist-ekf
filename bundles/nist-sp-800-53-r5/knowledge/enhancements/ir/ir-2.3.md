---
type: control_enhancement
title: IR-2.3 - Breach
description: Provide incident response training on how to identify and respond to a breach, including the organization’s
  process for reporting a breach.
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
  description: IR-2.3 - Breach is part of its parent SP 800-53 structure.
- name: IR-2 - Incident Response Training
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-2.md
  relation: enhances
  description: IR-2.3 enhances base control IR-2.
nist_id: IR-2.3
sort_id: ir-02.03
implementation_level: organization
parameter_ids: []
reference_links:
- '#ir-2'
---

# Summary

Provide incident response training on how to identify and respond to a breach, including the organization’s process for reporting a breach.

# Statement

Provide incident response training on how to identify and respond to a breach, including the organization’s process for reporting a breach.

# Guidance

For federal agencies, an incident that involves personally identifiable information is considered a breach. A breach results in the loss of control, compromise, unauthorized disclosure, unauthorized acquisition, or a similar occurrence where a person other than an authorized user accesses or potentially accesses personally identifiable information or an authorized user accesses or potentially accesses such information for other than authorized purposes. The incident response training emphasizes the obligation of individuals to report both confirmed and suspected breaches involving information in any medium or form, including paper, oral, and electronic. Incident response training includes tabletop exercises that simulate a breach. See [IR-2(1)](#ir-2.1).

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
