---
type: control
title: IR-3 - Incident Response Testing
description: 'Test the effectiveness of the incident response capability for the system {{ insert: param, ir-03_odp.01
  }} using the following tests: {{ insert: param, ir-03_odp.02 }}.'
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ir.md
  relation: part_of
  description: IR-3 - Incident Response Testing is part of its parent SP 800-53 structure.
- name: IR-3.1 - Automated Testing
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-3.1.md
  relation: has_enhancement
  description: IR-3 has enhancement IR-3.1.
- name: IR-3.2 - Coordination with Related Plans
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-3.2.md
  relation: has_enhancement
  description: IR-3 has enhancement IR-3.2.
- name: IR-3.3 - Continuous Improvement
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-3.3.md
  relation: has_enhancement
  description: IR-3 has enhancement IR-3.3.
nist_id: IR-3
sort_id: ir-03
implementation_level: organization
parameter_ids:
- ir-03_odp.01
- ir-03_odp.02
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#53be2fcf-cfd1-4bcb-896b-9a3b65c22098'
- '#122177fa-c4ed-485d-8345-3082c0fb9a06'
- '#cp-3'
- '#cp-4'
- '#ir-2'
- '#ir-4'
- '#ir-8'
- '#pm-14'
---

# Summary

Test the effectiveness of the incident response capability for the system {{ insert: param, ir-03_odp.01 }} using the following tests: {{ insert: param, ir-03_odp.02 }}.

# Statement

Test the effectiveness of the incident response capability for the system {{ insert: param, ir-03_odp.01 }} using the following tests: {{ insert: param, ir-03_odp.02 }}.

# Guidance

Organizations test incident response capabilities to determine their effectiveness and identify potential weaknesses or deficiencies. Incident response testing includes the use of checklists, walk-through or tabletop exercises, and simulations (parallel or full interrupt). Incident response testing can include a determination of the effects on organizational operations and assets and individuals due to incident response. The use of qualitative and quantitative data aids in determining the effectiveness of incident response processes.

# Parameters

- `ir-03_odp.01`
- `ir-03_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
