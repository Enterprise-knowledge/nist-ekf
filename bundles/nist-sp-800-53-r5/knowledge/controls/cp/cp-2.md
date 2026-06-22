---
type: control
title: CP-2 - Contingency Plan
description: SP 800-53 control CP-2.
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
- cp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/cp.md
  relation: part_of
  description: CP-2 - Contingency Plan is part of its parent SP 800-53 structure.
- name: CP-2.1 - Coordinate with Related Plans
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-2.1.md
  relation: has_enhancement
  description: CP-2 has enhancement CP-2.1.
- name: CP-2.2 - Capacity Planning
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-2.2.md
  relation: has_enhancement
  description: CP-2 has enhancement CP-2.2.
- name: CP-2.3 - Resume Mission and Business Functions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-2.3.md
  relation: has_enhancement
  description: CP-2 has enhancement CP-2.3.
- name: CP-2.4 - Resume All Mission and Business Functions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-2.4.md
  relation: has_enhancement
  description: CP-2 has enhancement CP-2.4.
- name: CP-2.5 - Continue Mission and Business Functions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-2.5.md
  relation: has_enhancement
  description: CP-2 has enhancement CP-2.5.
- name: CP-2.6 - Alternate Processing and Storage Sites
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-2.6.md
  relation: has_enhancement
  description: CP-2 has enhancement CP-2.6.
- name: CP-2.7 - Coordinate with External Service Providers
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-2.7.md
  relation: has_enhancement
  description: CP-2 has enhancement CP-2.7.
- name: CP-2.8 - Identify Critical Assets
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cp/cp-2.8.md
  relation: has_enhancement
  description: CP-2 has enhancement CP-2.8.
nist_id: CP-2
sort_id: cp-02
implementation_level: organization
parameter_ids:
- cp-2_prm_1
- cp-2_prm_2
- cp-2_prm_4
- cp-02_odp.01
- cp-02_odp.02
- cp-02_odp.03
- cp-02_odp.04
- cp-02_odp.05
- cp-02_odp.06
- cp-02_odp.07
reference_links:
- '#bc39f179-c735-4da2-b7a7-b2b622119755'
- '#d4296805-2dca-4c63-a95f-eeccaa826aec'
- '#cp-3'
- '#cp-4'
- '#cp-6'
- '#cp-7'
- '#cp-8'
- '#cp-9'
- '#cp-10'
- '#cp-11'
- '#cp-13'
- '#ir-4'
- '#ir-6'
- '#ir-8'
- '#ir-9'
- '#ma-6'
- '#mp-2'
- '#mp-4'
- '#mp-5'
- '#pl-2'
- '#pm-8'
- '#pm-11'
- '#sa-15'
- '#sa-20'
- '#sc-7'
- '#sc-23'
- '#si-12'
---

# Summary

SP 800-53 control CP-2.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Contingency planning for systems is part of an overall program for achieving continuity of operations for organizational mission and business functions. Contingency planning addresses system restoration and implementation of alternative mission or business processes when systems are compromised or breached. Contingency planning is considered throughout the system development life cycle and is a fundamental part of the system design. Systems can be designed for redundancy, to provide backup capabilities, and for resilience. Contingency plans reflect the degree of restoration required for organizational systems since not all systems need to fully recover to achieve the level of continuity of operations desired. System recovery objectives reflect applicable laws, executive orders, directives, regulations, policies, standards, guidelines, organizational risk tolerance, and system impact level.

Actions addressed in contingency plans include orderly system degradation, system shutdown, fallback to a manual mode, alternate information flows, and operating in modes reserved for when systems are under attack. By coordinating contingency planning with incident handling activities, organizations ensure that the necessary planning activities are in place and activated in the event of an incident. Organizations consider whether continuity of operations during an incident conflicts with the capability to automatically disable the system, as specified in [IR-4(5)](#ir-4.5) . Incident response planning is part of contingency planning for organizations and is addressed in the [IR](#ir) (Incident Response) family.

# Parameters

- `cp-2_prm_1`
- `cp-2_prm_2`
- `cp-2_prm_4`
- `cp-02_odp.01`
- `cp-02_odp.02`
- `cp-02_odp.03`
- `cp-02_odp.04`
- `cp-02_odp.05`
- `cp-02_odp.06`
- `cp-02_odp.07`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
