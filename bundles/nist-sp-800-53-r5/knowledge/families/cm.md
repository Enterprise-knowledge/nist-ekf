---
type: control_family
title: CM - Configuration Management
description: SP 800-53 control family for Configuration Management.
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control-family
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
- name: The Controls
  path: /bundles/nist-sp-800-53-r5/knowledge/sections/controls.md
  relation: part_of
  description: This family is part of the controls section.
- name: CM-1 - Policy and Procedures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-1.md
  relation: contains
  description: The family contains control CM-1.
- name: CM-2 - Baseline Configuration
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-2.md
  relation: contains
  description: The family contains control CM-2.
- name: CM-3 - Configuration Change Control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-3.md
  relation: contains
  description: The family contains control CM-3.
- name: CM-4 - Impact Analyses
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-4.md
  relation: contains
  description: The family contains control CM-4.
- name: CM-5 - Access Restrictions for Change
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-5.md
  relation: contains
  description: The family contains control CM-5.
- name: CM-6 - Configuration Settings
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-6.md
  relation: contains
  description: The family contains control CM-6.
- name: CM-7 - Least Functionality
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-7.md
  relation: contains
  description: The family contains control CM-7.
- name: CM-8 - System Component Inventory
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-8.md
  relation: contains
  description: The family contains control CM-8.
- name: CM-9 - Configuration Management Plan
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-9.md
  relation: contains
  description: The family contains control CM-9.
- name: CM-10 - Software Usage Restrictions
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-10.md
  relation: contains
  description: The family contains control CM-10.
- name: CM-11 - User-installed Software
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-11.md
  relation: contains
  description: The family contains control CM-11.
- name: CM-12 - Information Location
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-12.md
  relation: contains
  description: The family contains control CM-12.
- name: CM-13 - Data Action Mapping
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-13.md
  relation: contains
  description: The family contains control CM-13.
- name: CM-14 - Signed Components
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-14.md
  relation: contains
  description: The family contains control CM-14.
nist_id: CM
base_control_count: 14
control_enhancement_count: 52
---

# Summary

The Configuration Management family contains 14 base controls and 52 control enhancements in the NIST OSCAL catalog.

# Controls

- [CM-1 - Policy and Procedures](../controls/cm/cm-1.md) - SP 800-53 control CM-1.
- [CM-2 - Baseline Configuration](../controls/cm/cm-2.md) - SP 800-53 control CM-2.
- [CM-3 - Configuration Change Control](../controls/cm/cm-3.md) - SP 800-53 control CM-3.
- [CM-4 - Impact Analyses](../controls/cm/cm-4.md) - Analyze changes to the system to determine potential security and privacy impacts prior to change implementation.
- [CM-5 - Access Restrictions for Change](../controls/cm/cm-5.md) - Define, document, approve, and enforce physical and logical access restrictions associated with changes to the system.
- [CM-6 - Configuration Settings](../controls/cm/cm-6.md) - SP 800-53 control CM-6.
- [CM-7 - Least Functionality](../controls/cm/cm-7.md) - SP 800-53 control CM-7.
- [CM-8 - System Component Inventory](../controls/cm/cm-8.md) - SP 800-53 control CM-8.
- [CM-9 - Configuration Management Plan](../controls/cm/cm-9.md) - Develop, document, and implement a configuration management plan for the system that:
- [CM-10 - Software Usage Restrictions](../controls/cm/cm-10.md) - SP 800-53 control CM-10.
- [CM-11 - User-installed Software](../controls/cm/cm-11.md) - SP 800-53 control CM-11.
- [CM-12 - Information Location](../controls/cm/cm-12.md) - SP 800-53 control CM-12.
- [CM-13 - Data Action Mapping](../controls/cm/cm-13.md) - Develop and document a map of system data actions.
- [CM-14 - Signed Components](../controls/cm/cm-14.md) - Prevent the installation of {{ insert: param, cm-14_prm_1 }} without verification that the component has been digitally signed using a certificate that is recognized and approved by the organization.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
