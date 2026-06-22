---
type: control
title: MA-2 - Controlled Maintenance
description: SP 800-53 control MA-2.
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
- ma
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ma.md
  relation: part_of
  description: MA-2 - Controlled Maintenance is part of its parent SP 800-53 structure.
- name: MA-2.1 - Record Content
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-2.1.md
  relation: has_enhancement
  description: MA-2 has enhancement MA-2.1.
- name: MA-2.2 - Automated Maintenance Activities
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-2.2.md
  relation: has_enhancement
  description: MA-2 has enhancement MA-2.2.
nist_id: MA-2
sort_id: ma-02
implementation_level: organization
parameter_ids:
- ma-02_odp.01
- ma-02_odp.02
- ma-02_odp.03
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#4c501da5-9d79-4cb6-ba80-97260e1ce327'
- '#cm-2'
- '#cm-3'
- '#cm-4'
- '#cm-5'
- '#cm-8'
- '#ma-4'
- '#mp-6'
- '#pe-16'
- '#si-2'
- '#sr-3'
- '#sr-4'
- '#sr-11'
---

# Summary

SP 800-53 control MA-2.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Controlling system maintenance addresses the information security aspects of the system maintenance program and applies to all types of maintenance to system components conducted by local or nonlocal entities. Maintenance includes peripherals such as scanners, copiers, and printers. Information necessary for creating effective maintenance records includes the date and time of maintenance, a description of the maintenance performed, names of the individuals or group performing the maintenance, name of the escort, and system components or equipment that are removed or replaced. Organizations consider supply chain-related risks associated with replacement components for systems.

# Parameters

- `ma-02_odp.01`
- `ma-02_odp.02`
- `ma-02_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
