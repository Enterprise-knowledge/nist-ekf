---
type: control_enhancement
title: SR-6.1 - Testing and Analysis
description: 'Employ {{ insert: param, sr-06.01_odp.01 }} of the following supply chain elements, processes, and
  actors associated with the system, system component, or system service: {{ insert: param, sr-06.01_odp.02 }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-6.md
  relation: part_of
  description: SR-6.1 - Testing and Analysis is part of its parent SP 800-53 structure.
- name: SR-6 - Supplier Assessments and Reviews
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-6.md
  relation: enhances
  description: SR-6.1 enhances base control SR-6.
nist_id: SR-6.1
sort_id: sr-06.01
implementation_level: organization
parameter_ids:
- sr-06.01_odp.01
- sr-06.01_odp.02
reference_links:
- '#sr-6'
- '#ca-8'
- '#si-4'
---

# Summary

Employ {{ insert: param, sr-06.01_odp.01 }} of the following supply chain elements, processes, and actors associated with the system, system component, or system service: {{ insert: param, sr-06.01_odp.02 }}.

# Statement

Employ {{ insert: param, sr-06.01_odp.01 }} of the following supply chain elements, processes, and actors associated with the system, system component, or system service: {{ insert: param, sr-06.01_odp.02 }}.

# Guidance

Relationships between entities and procedures within the supply chain, including development and delivery, are considered. Supply chain elements include organizations, entities, or tools that are used for the research and development, design, manufacturing, acquisition, delivery, integration, operations, maintenance, and disposal of systems, system components, or system services. Supply chain processes include supply chain risk management programs; SCRM strategies and implementation plans; personnel and physical security programs; hardware, software, and firmware development processes; configuration management tools, techniques, and measures to maintain provenance; shipping and handling procedures; and programs, processes, or procedures associated with the production and distribution of supply chain elements. Supply chain actors are individuals with specific roles and responsibilities in the supply chain. The evidence generated and collected during analyses and testing of supply chain elements, processes, and actors is documented and used to inform organizational risk management activities and decisions.

# Parameters

- `sr-06.01_odp.01`
- `sr-06.01_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
