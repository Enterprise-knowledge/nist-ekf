---
type: control_enhancement
title: SR-4.1 - Identity
description: 'Establish and maintain unique identification of the following supply chain elements, processes, and
  personnel associated with the identified system and critical system components: {{ insert: param, sr-04.01_odp
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
  description: SR-4.1 - Identity is part of its parent SP 800-53 structure.
- name: SR-4 - Provenance
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-4.md
  relation: enhances
  description: SR-4.1 enhances base control SR-4.
nist_id: SR-4.1
sort_id: sr-04.01
implementation_level: organization
parameter_ids:
- sr-04.01_odp
reference_links:
- '#sr-4'
- '#ia-2'
- '#ia-8'
- '#pe-16'
---

# Summary

Establish and maintain unique identification of the following supply chain elements, processes, and personnel associated with the identified system and critical system components: {{ insert: param, sr-04.01_odp }}.

# Statement

Establish and maintain unique identification of the following supply chain elements, processes, and personnel associated with the identified system and critical system components: {{ insert: param, sr-04.01_odp }}.

# Guidance

Knowing who and what is in the supply chains of organizations is critical to gaining visibility into supply chain activities. Visibility into supply chain activities is also important for monitoring and identifying high-risk events and activities. Without reasonable visibility into supply chains elements, processes, and personnel, it is very difficult for organizations to understand and manage risk and reduce their susceptibility to adverse events. Supply chain elements include organizations, entities, or tools used for the research and development, design, manufacturing, acquisition, delivery, integration, operations, maintenance, and disposal of systems and system components. Supply chain processes include development processes for hardware, software, and firmware; shipping and handling procedures; configuration management tools, techniques, and measures to maintain provenance; personnel and physical security programs; or other programs, processes, or procedures associated with the production and distribution of supply chain elements. Supply chain personnel are individuals with specific roles and responsibilities related to the secure the research and development, design, manufacturing, acquisition, delivery, integration, operations and maintenance, and disposal of a system or system component. Identification methods are sufficient to support an investigation in case of a supply chain change (e.g. if a supply company is purchased), compromise, or event.

# Parameters

- `sr-04.01_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
