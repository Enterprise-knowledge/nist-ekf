---
type: control_family
title: PE - Physical and Environmental Protection
description: SP 800-53 control family for Physical and Environmental Protection.
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
- pe
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
- name: PE-1 - Policy and Procedures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-1.md
  relation: contains
  description: The family contains control PE-1.
- name: PE-2 - Physical Access Authorizations
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-2.md
  relation: contains
  description: The family contains control PE-2.
- name: PE-3 - Physical Access Control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-3.md
  relation: contains
  description: The family contains control PE-3.
- name: PE-4 - Access Control for Transmission
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-4.md
  relation: contains
  description: The family contains control PE-4.
- name: PE-5 - Access Control for Output Devices
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-5.md
  relation: contains
  description: The family contains control PE-5.
- name: PE-6 - Monitoring Physical Access
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-6.md
  relation: contains
  description: The family contains control PE-6.
- name: PE-7 - Visitor Control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-7.md
  relation: contains
  description: The family contains control PE-7.
- name: PE-8 - Visitor Access Records
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-8.md
  relation: contains
  description: The family contains control PE-8.
- name: PE-9 - Power Equipment and Cabling
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-9.md
  relation: contains
  description: The family contains control PE-9.
- name: PE-10 - Emergency Shutoff
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-10.md
  relation: contains
  description: The family contains control PE-10.
- name: PE-11 - Emergency Power
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-11.md
  relation: contains
  description: The family contains control PE-11.
- name: PE-12 - Emergency Lighting
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-12.md
  relation: contains
  description: The family contains control PE-12.
- name: PE-13 - Fire Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-13.md
  relation: contains
  description: The family contains control PE-13.
- name: PE-14 - Environmental Controls
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-14.md
  relation: contains
  description: The family contains control PE-14.
- name: PE-15 - Water Damage Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-15.md
  relation: contains
  description: The family contains control PE-15.
- name: PE-16 - Delivery and Removal
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-16.md
  relation: contains
  description: The family contains control PE-16.
- name: PE-17 - Alternate Work Site
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-17.md
  relation: contains
  description: The family contains control PE-17.
- name: PE-18 - Location of System Components
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-18.md
  relation: contains
  description: The family contains control PE-18.
- name: PE-19 - Information Leakage
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-19.md
  relation: contains
  description: The family contains control PE-19.
- name: PE-20 - Asset Monitoring and Tracking
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-20.md
  relation: contains
  description: The family contains control PE-20.
- name: PE-21 - Electromagnetic Pulse Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-21.md
  relation: contains
  description: The family contains control PE-21.
- name: PE-22 - Component Marking
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-22.md
  relation: contains
  description: The family contains control PE-22.
- name: PE-23 - Facility Location
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-23.md
  relation: contains
  description: The family contains control PE-23.
nist_id: PE
base_control_count: 23
control_enhancement_count: 36
---

# Summary

The Physical and Environmental Protection family contains 23 base controls and 36 control enhancements in the NIST OSCAL catalog.

# Controls

- [PE-1 - Policy and Procedures](../controls/pe/pe-1.md) - SP 800-53 control PE-1.
- [PE-2 - Physical Access Authorizations](../controls/pe/pe-2.md) - SP 800-53 control PE-2.
- [PE-3 - Physical Access Control](../controls/pe/pe-3.md) - SP 800-53 control PE-3.
- [PE-4 - Access Control for Transmission](../controls/pe/pe-4.md) - Control physical access to {{ insert: param, pe-04_odp.01 }} within organizational facilities using {{ insert: param, pe-04_odp.02 }}.
- [PE-5 - Access Control for Output Devices](../controls/pe/pe-5.md) - Control physical access to output from {{ insert: param, pe-05_odp }} to prevent unauthorized individuals from obtaining the output.
- [PE-6 - Monitoring Physical Access](../controls/pe/pe-6.md) - SP 800-53 control PE-6.
- [PE-7 - Visitor Control](../controls/pe/pe-7.md) - SP 800-53 control PE-7.
- [PE-8 - Visitor Access Records](../controls/pe/pe-8.md) - SP 800-53 control PE-8.
- [PE-9 - Power Equipment and Cabling](../controls/pe/pe-9.md) - Protect power equipment and power cabling for the system from damage and destruction.
- [PE-10 - Emergency Shutoff](../controls/pe/pe-10.md) - SP 800-53 control PE-10.
- [PE-11 - Emergency Power](../controls/pe/pe-11.md) - Provide an uninterruptible power supply to facilitate {{ insert: param, pe-11_odp }} in the event of a primary power source loss.
- [PE-12 - Emergency Lighting](../controls/pe/pe-12.md) - Employ and maintain automatic emergency lighting for the system that activates in the event of a power outage or disruption and that covers emergency exits and evacuation routes within the facility.
- [PE-13 - Fire Protection](../controls/pe/pe-13.md) - Employ and maintain fire detection and suppression systems that are supported by an independent energy source.
- [PE-14 - Environmental Controls](../controls/pe/pe-14.md) - SP 800-53 control PE-14.
- [PE-15 - Water Damage Protection](../controls/pe/pe-15.md) - Protect the system from damage resulting from water leakage by providing master shutoff or isolation valves that are accessible, working properly, and known to key personnel.
- [PE-16 - Delivery and Removal](../controls/pe/pe-16.md) - SP 800-53 control PE-16.
- [PE-17 - Alternate Work Site](../controls/pe/pe-17.md) - SP 800-53 control PE-17.
- [PE-18 - Location of System Components](../controls/pe/pe-18.md) - Position system components within the facility to minimize potential damage from {{ insert: param, pe-18_odp }} and to minimize the opportunity for unauthorized access.
- [PE-19 - Information Leakage](../controls/pe/pe-19.md) - Protect the system from information leakage due to electromagnetic signals emanations.
- [PE-20 - Asset Monitoring and Tracking](../controls/pe/pe-20.md) - Employ {{ insert: param, pe-20_odp.01 }} to track and monitor the location and movement of {{ insert: param, pe-20_odp.02 }} within {{ insert: param, pe-20_odp.03 }}.
- [PE-21 - Electromagnetic Pulse Protection](../controls/pe/pe-21.md) - Employ {{ insert: param, pe-21_odp.01 }} against electromagnetic pulse damage for {{ insert: param, pe-21_odp.02 }}.
- [PE-22 - Component Marking](../controls/pe/pe-22.md) - Mark {{ insert: param, pe-22_odp }} indicating the impact level or classification level of the information permitted to be processed, stored, or transmitted by the hardware component.
- [PE-23 - Facility Location](../controls/pe/pe-23.md) - SP 800-53 control PE-23.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
