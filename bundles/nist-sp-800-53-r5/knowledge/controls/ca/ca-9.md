---
type: control
title: CA-9 - Internal System Connections
description: SP 800-53 control CA-9.
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
- ca
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ca.md
  relation: part_of
  description: CA-9 - Internal System Connections is part of its parent SP 800-53 structure.
- name: CA-9.1 - Compliance Checks
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-9.1.md
  relation: has_enhancement
  description: CA-9 has enhancement CA-9.1.
nist_id: CA-9
sort_id: ca-09
implementation_level: organization
parameter_ids:
- ca-09_odp.01
- ca-09_odp.02
- ca-09_odp.03
reference_links:
- '#0f66be67-85e7-4ca6-bd19-39453e9f4394'
- '#4c501da5-9d79-4cb6-ba80-97260e1ce327'
- '#ac-3'
- '#ac-4'
- '#ac-18'
- '#ac-19'
- '#cm-2'
- '#ia-3'
- '#sc-7'
- '#si-12'
---

# Summary

SP 800-53 control CA-9.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Internal system connections are connections between organizational systems and separate constituent system components (i.e., connections between components that are part of the same system) including components used for system development. Intra-system connections include connections with mobile devices, notebook and desktop computers, tablets, printers, copiers, facsimile machines, scanners, sensors, and servers. Instead of authorizing each internal system connection individually, organizations can authorize internal connections for a class of system components with common characteristics and/or configurations, including printers, scanners, and copiers with a specified processing, transmission, and storage capability or smart phones and tablets with a specific baseline configuration. The continued need for an internal system connection is reviewed from the perspective of whether it provides support for organizational missions or business functions.

# Parameters

- `ca-09_odp.01`
- `ca-09_odp.02`
- `ca-09_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
