---
type: control
title: CM-8 - System Component Inventory
description: SP 800-53 control CM-8.
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
- cm
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/cm.md
  relation: part_of
  description: CM-8 - System Component Inventory is part of its parent SP 800-53 structure.
- name: CM-8.1 - Updates During Installation and Removal
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-8.1.md
  relation: has_enhancement
  description: CM-8 has enhancement CM-8.1.
- name: CM-8.2 - Automated Maintenance
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-8.2.md
  relation: has_enhancement
  description: CM-8 has enhancement CM-8.2.
- name: CM-8.3 - Automated Unauthorized Component Detection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-8.3.md
  relation: has_enhancement
  description: CM-8 has enhancement CM-8.3.
- name: CM-8.4 - Accountability Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-8.4.md
  relation: has_enhancement
  description: CM-8 has enhancement CM-8.4.
- name: CM-8.5 - No Duplicate Accounting of Components
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-8.5.md
  relation: has_enhancement
  description: CM-8 has enhancement CM-8.5.
- name: CM-8.6 - Assessed Configurations and Approved Deviations
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-8.6.md
  relation: has_enhancement
  description: CM-8 has enhancement CM-8.6.
- name: CM-8.7 - Centralized Repository
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-8.7.md
  relation: has_enhancement
  description: CM-8 has enhancement CM-8.7.
- name: CM-8.8 - Automated Location Tracking
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-8.8.md
  relation: has_enhancement
  description: CM-8 has enhancement CM-8.8.
- name: CM-8.9 - Assignment of Components to Systems
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-8.9.md
  relation: has_enhancement
  description: CM-8 has enhancement CM-8.9.
nist_id: CM-8
sort_id: cm-08
implementation_level: organization
parameter_ids:
- cm-08_odp.01
- cm-08_odp.02
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#110e26af-4765-49e1-8740-6750f83fcda1'
- '#e7942589-e267-4a5a-a3d9-f39a7aae81f0'
- '#8306620b-1920-4d73-8b21-12008528595f'
- '#20db4e66-e257-450c-b2e4-2bb9a62a2c88'
- '#70402863-5078-43af-9a6c-e11b0f3ec370'
- '#996241f8-f692-42d5-91f1-ce8b752e39e6'
- '#cm-2'
- '#cm-7'
- '#cm-9'
- '#cm-10'
- '#cm-11'
- '#cm-13'
- '#cp-2'
- '#cp-9'
- '#ma-2'
- '#ma-6'
- '#pe-20'
- '#pl-9'
- '#pm-5'
- '#sa-4'
- '#sa-5'
- '#si-2'
- '#sr-4'
---

# Summary

SP 800-53 control CM-8.

# Statement

No statement text was present in the OSCAL record.

# Guidance

System components are discrete, identifiable information technology assets that include hardware, software, and firmware. Organizations may choose to implement centralized system component inventories that include components from all organizational systems. In such situations, organizations ensure that the inventories include system-specific information required for component accountability. The information necessary for effective accountability of system components includes the system name, software owners, software version numbers, hardware inventory specifications, software license information, and for networked components, the machine names and network addresses across all implemented protocols (e.g., IPv4, IPv6). Inventory specifications include date of receipt, cost, model, serial number, manufacturer, supplier information, component type, and physical location.

Preventing duplicate accounting of system components addresses the lack of accountability that occurs when component ownership and system association is not known, especially in large or complex connected systems. Effective prevention of duplicate accounting of system components necessitates use of a unique identifier for each component. For software inventory, centrally managed software that is accessed via other systems is addressed as a component of the system on which it is installed and managed. Software installed on multiple organizational systems and managed at the system level is addressed for each individual system and may appear more than once in a centralized component inventory, necessitating a system association for each software instance in the centralized inventory to avoid duplicate accounting of components. Scanning systems implementing multiple network protocols (e.g., IPv4 and IPv6) can result in duplicate components being identified in different address spaces. The implementation of [CM-8(7)](#cm-8.7) can help to eliminate duplicate accounting of components.

# Parameters

- `cm-08_odp.01`
- `cm-08_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
