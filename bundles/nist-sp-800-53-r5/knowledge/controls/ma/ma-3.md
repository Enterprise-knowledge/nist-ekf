---
type: control
title: MA-3 - Maintenance Tools
description: SP 800-53 control MA-3.
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
  description: MA-3 - Maintenance Tools is part of its parent SP 800-53 structure.
- name: MA-3.1 - Inspect Tools
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-3.1.md
  relation: has_enhancement
  description: MA-3 has enhancement MA-3.1.
- name: MA-3.2 - Inspect Media
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-3.2.md
  relation: has_enhancement
  description: MA-3 has enhancement MA-3.2.
- name: MA-3.3 - Prevent Unauthorized Removal
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-3.3.md
  relation: has_enhancement
  description: MA-3 has enhancement MA-3.3.
- name: MA-3.4 - Restricted Tool Use
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-3.4.md
  relation: has_enhancement
  description: MA-3 has enhancement MA-3.4.
- name: MA-3.5 - Execution with Privilege
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-3.5.md
  relation: has_enhancement
  description: MA-3 has enhancement MA-3.5.
- name: MA-3.6 - Software Updates and Patches
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ma/ma-3.6.md
  relation: has_enhancement
  description: MA-3 has enhancement MA-3.6.
nist_id: MA-3
sort_id: ma-03
implementation_level: organization
parameter_ids:
- ma-03_odp
reference_links:
- '#a5b1d18d-e670-4586-9e6d-4a88b7ba3df6'
- '#ma-2'
- '#pe-16'
---

# Summary

SP 800-53 control MA-3.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Approving, controlling, monitoring, and reviewing maintenance tools address security-related issues associated with maintenance tools that are not within system authorization boundaries and are used specifically for diagnostic and repair actions on organizational systems. Organizations have flexibility in determining roles for the approval of maintenance tools and how that approval is documented. A periodic review of maintenance tools facilitates the withdrawal of approval for outdated, unsupported, irrelevant, or no-longer-used tools. Maintenance tools can include hardware, software, and firmware items and may be pre-installed, brought in with maintenance personnel on media, cloud-based, or downloaded from a website. Such tools can be vehicles for transporting malicious code, either intentionally or unintentionally, into a facility and subsequently into systems. Maintenance tools can include hardware and software diagnostic test equipment and packet sniffers. The hardware and software components that support maintenance and are a part of the system (including the software implementing utilities such as "ping," "ls," "ipconfig," or the hardware and software implementing the monitoring port of an Ethernet switch) are not addressed by maintenance tools.

# Parameters

- `ma-03_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
