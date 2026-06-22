---
type: control
title: SR-4 - Provenance
description: 'Document, monitor, and maintain valid provenance of the following systems, system components, and
  associated data: {{ insert: param, sr-04_odp }}.'
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/sr.md
  relation: part_of
  description: SR-4 - Provenance is part of its parent SP 800-53 structure.
- name: SR-4.1 - Identity
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sr/sr-4.1.md
  relation: has_enhancement
  description: SR-4 has enhancement SR-4.1.
- name: SR-4.2 - Track and Trace
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sr/sr-4.2.md
  relation: has_enhancement
  description: SR-4 has enhancement SR-4.2.
- name: SR-4.3 - Validate as Genuine and Not Altered
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sr/sr-4.3.md
  relation: has_enhancement
  description: SR-4 has enhancement SR-4.3.
- name: SR-4.4 - Supply Chain Integrity — Pedigree
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sr/sr-4.4.md
  relation: has_enhancement
  description: SR-4 has enhancement SR-4.4.
nist_id: SR-4
sort_id: sr-04
implementation_level: organization
parameter_ids:
- sr-04_odp
reference_links:
- '#4ff10ed3-d8fe-4246-99e3-443045e27482'
- '#0f963c17-ab5a-432a-a867-91eac550309b'
- '#21caa535-1154-4369-ba7b-32c309fee0f7'
- '#863caf2a-978a-4260-9e8d-4a8929bce40c'
- '#15a95e24-65b6-4686-bc18-90855a10457d'
- '#e3cc0520-a366-4fc9-abc2-5272db7e3564'
- '#e8e84963-14fc-4c3a-be05-b412a5d37cd2'
- '#e24b06cc-9129-4998-a76a-65c3d7a576ba'
- '#a2590922-82f3-4277-83c0-ca5bee06dba4'
- '#38ff38f0-1366-4f50-a4c9-26a39aacee16'
- '#cm-8'
- '#ma-2'
- '#ma-6'
- '#ra-9'
- '#sa-3'
- '#sa-8'
- '#si-4'
---

# Summary

Document, monitor, and maintain valid provenance of the following systems, system components, and associated data: {{ insert: param, sr-04_odp }}.

# Statement

Document, monitor, and maintain valid provenance of the following systems, system components, and associated data: {{ insert: param, sr-04_odp }}.

# Guidance

Every system and system component has a point of origin and may be changed throughout its existence. Provenance is the chronology of the origin, development, ownership, location, and changes to a system or system component and associated data. It may also include personnel and processes used to interact with or make modifications to the system, component, or associated data. Organizations consider developing procedures (see [SR-1](#sr-1) ) for allocating responsibilities for the creation, maintenance, and monitoring of provenance for systems and system components; transferring provenance documentation and responsibility between organizations; and preventing and monitoring for unauthorized changes to the provenance records. Organizations have methods to document, monitor, and maintain valid provenance baselines for systems, system components, and related data. These actions help track, assess, and document any changes to the provenance, including changes in supply chain elements or configuration, and help ensure non-repudiation of provenance information and the provenance change records. Provenance considerations are addressed throughout the system development life cycle and incorporated into contracts and other arrangements, as appropriate.

# Parameters

- `sr-04_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
