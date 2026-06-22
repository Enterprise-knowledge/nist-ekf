---
type: control_enhancement
title: SR-4.2 - Track and Trace
description: 'Establish and maintain unique identification of the following systems and critical system components
  for tracking through the supply chain: {{ insert: param, sr-04.02_odp }}.'
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
- sr
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-4.md
  relation: part_of
  description: SR-4.2 - Track and Trace is part of its parent SP 800-53 structure.
- name: SR-4 - Provenance
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-4.md
  relation: enhances
  description: SR-4.2 enhances base control SR-4.
nist_id: SR-4.2
sort_id: sr-04.02
implementation_level: organization
parameter_ids:
- sr-04.02_odp
reference_links:
- '#sr-4'
- '#ia-2'
- '#ia-8'
- '#pe-16'
- '#pl-2'
---

# Summary

Establish and maintain unique identification of the following systems and critical system components for tracking through the supply chain: {{ insert: param, sr-04.02_odp }}.

# Statement

Establish and maintain unique identification of the following systems and critical system components for tracking through the supply chain: {{ insert: param, sr-04.02_odp }}.

# Guidance

Tracking the unique identification of systems and system components during development and transport activities provides a foundational identity structure for the establishment and maintenance of provenance. For example, system components may be labeled using serial numbers or tagged using radio-frequency identification tags. Labels and tags can help provide better visibility into the provenance of a system or system component. A system or system component may have more than one unique identifier. Identification methods are sufficient to support a forensic investigation after a supply chain compromise or event.

# Parameters

- `sr-04.02_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
