---
type: control_enhancement
title: PE-3.5 - Tamper Protection
description: 'Employ {{ insert: param, pe-03.05_odp.01 }} to {{ insert: param, pe-03.05_odp.02 }} physical tampering
  or alteration of {{ insert: param, pe-03.05_odp.03 }} within the system.'
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
- pe
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-3.md
  relation: part_of
  description: PE-3.5 - Tamper Protection is part of its parent SP 800-53 structure.
- name: PE-3 - Physical Access Control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-3.md
  relation: enhances
  description: PE-3.5 enhances base control PE-3.
nist_id: PE-3.5
sort_id: pe-03.05
implementation_level: organization
parameter_ids:
- pe-03.05_odp.01
- pe-03.05_odp.02
- pe-03.05_odp.03
reference_links:
- '#pe-3'
- '#sa-16'
- '#sr-9'
- '#sr-11'
---

# Summary

Employ {{ insert: param, pe-03.05_odp.01 }} to {{ insert: param, pe-03.05_odp.02 }} physical tampering or alteration of {{ insert: param, pe-03.05_odp.03 }} within the system.

# Statement

Employ {{ insert: param, pe-03.05_odp.01 }} to {{ insert: param, pe-03.05_odp.02 }} physical tampering or alteration of {{ insert: param, pe-03.05_odp.03 }} within the system.

# Guidance

Organizations can implement tamper detection and prevention at selected hardware components or implement tamper detection at some components and tamper prevention at other components. Detection and prevention activities can employ many types of anti-tamper technologies, including tamper-detection seals and anti-tamper coatings. Anti-tamper programs help to detect hardware alterations through counterfeiting and other supply chain-related risks.

# Parameters

- `pe-03.05_odp.01`
- `pe-03.05_odp.02`
- `pe-03.05_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
