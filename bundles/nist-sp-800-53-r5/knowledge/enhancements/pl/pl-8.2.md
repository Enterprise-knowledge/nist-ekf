---
type: control_enhancement
title: PL-8.2 - Supplier Diversity
description: 'Require that {{ insert: param, pl-08.02_odp.01 }} allocated to {{ insert: param, pl-08.02_odp.02 }}
  are obtained from different suppliers.'
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
- pl
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pl/pl-8.md
  relation: part_of
  description: PL-8.2 - Supplier Diversity is part of its parent SP 800-53 structure.
- name: PL-8 - Security and Privacy Architectures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pl/pl-8.md
  relation: enhances
  description: PL-8.2 enhances base control PL-8.
nist_id: PL-8.2
sort_id: pl-08.02
implementation_level: organization
parameter_ids:
- pl-08.02_odp.01
- pl-08.02_odp.02
reference_links:
- '#pl-8'
- '#sc-29'
- '#sr-3'
---

# Summary

Require that {{ insert: param, pl-08.02_odp.01 }} allocated to {{ insert: param, pl-08.02_odp.02 }} are obtained from different suppliers.

# Statement

Require that {{ insert: param, pl-08.02_odp.01 }} allocated to {{ insert: param, pl-08.02_odp.02 }} are obtained from different suppliers.

# Guidance

Information technology products have different strengths and weaknesses. Providing a broad spectrum of products complements the individual offerings. For example, vendors offering malicious code protection typically update their products at different times, often developing solutions for known viruses, Trojans, or worms based on their priorities and development schedules. By deploying different products at different locations, there is an increased likelihood that at least one of the products will detect the malicious code. With respect to privacy, vendors may offer products that track personally identifiable information in systems. Products may use different tracking methods. Using multiple products may result in more assurance that personally identifiable information is inventoried.

# Parameters

- `pl-08.02_odp.01`
- `pl-08.02_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
