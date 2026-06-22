---
type: control_enhancement
title: SR-4.4 - Supply Chain Integrity — Pedigree
description: 'Employ {{ insert: param, sr-04.04_odp.01 }} and conduct {{ insert: param, sr-04.04_odp.02 }} to ensure
  the integrity of the system and system components by validating the internal composition and provenance of critical
  o'
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
  description: SR-4.4 - Supply Chain Integrity — Pedigree is part of its parent SP 800-53 structure.
- name: SR-4 - Provenance
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-4.md
  relation: enhances
  description: SR-4.4 enhances base control SR-4.
nist_id: SR-4.4
sort_id: sr-04.04
implementation_level: organization
parameter_ids:
- sr-04.04_odp.01
- sr-04.04_odp.02
reference_links:
- '#sr-4'
- '#ra-3'
---

# Summary

Employ {{ insert: param, sr-04.04_odp.01 }} and conduct {{ insert: param, sr-04.04_odp.02 }} to ensure the integrity of the system and system components by validating the internal composition and provenance of critical o

# Statement

Employ {{ insert: param, sr-04.04_odp.01 }} and conduct {{ insert: param, sr-04.04_odp.02 }} to ensure the integrity of the system and system components by validating the internal composition and provenance of critical or mission-essential technologies, products, and services.

# Guidance

Authoritative information regarding the internal composition of system components and the provenance of technology, products, and services provides a strong basis for trust. The validation of the internal composition and provenance of technologies, products, and services is referred to as the pedigree. For microelectronics, this includes material composition of components. For software this includes the composition of open-source and proprietary code, including the version of the component at a given point in time. Pedigrees increase the assurance that the claims suppliers assert about the internal composition and provenance of the products, services, and technologies they provide are valid. The validation of the internal composition and provenance can be achieved by various evidentiary artifacts or records that manufacturers and suppliers produce during the research and development, design, manufacturing, acquisition, delivery, integration, operations and maintenance, and disposal of technology, products, and services. Evidentiary artifacts include, but are not limited to, software identification (SWID) tags, software component inventory, the manufacturers’ declarations of platform attributes (e.g., serial numbers, hardware component inventory), and measurements (e.g., firmware hashes) that are tightly bound to the hardware itself.

# Parameters

- `sr-04.04_odp.01`
- `sr-04.04_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
