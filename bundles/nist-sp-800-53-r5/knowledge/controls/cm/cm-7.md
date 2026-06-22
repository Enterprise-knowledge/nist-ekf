---
type: control
title: CM-7 - Least Functionality
description: SP 800-53 control CM-7.
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
  description: CM-7 - Least Functionality is part of its parent SP 800-53 structure.
- name: CM-7.1 - Periodic Review
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-7.1.md
  relation: has_enhancement
  description: CM-7 has enhancement CM-7.1.
- name: CM-7.2 - Prevent Program Execution
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-7.2.md
  relation: has_enhancement
  description: CM-7 has enhancement CM-7.2.
- name: CM-7.3 - Registration Compliance
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-7.3.md
  relation: has_enhancement
  description: CM-7 has enhancement CM-7.3.
- name: CM-7.4 - Unauthorized Software — Deny-by-exception
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-7.4.md
  relation: has_enhancement
  description: CM-7 has enhancement CM-7.4.
- name: CM-7.5 - Authorized Software — Allow-by-exception
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-7.5.md
  relation: has_enhancement
  description: CM-7 has enhancement CM-7.5.
- name: CM-7.6 - Confined Environments with Limited Privileges
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-7.6.md
  relation: has_enhancement
  description: CM-7 has enhancement CM-7.6.
- name: CM-7.7 - Code Execution in Protected Environments
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-7.7.md
  relation: has_enhancement
  description: CM-7 has enhancement CM-7.7.
- name: CM-7.8 - Binary or Machine Executable Code
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-7.8.md
  relation: has_enhancement
  description: CM-7 has enhancement CM-7.8.
- name: CM-7.9 - Prohibiting The Use of Unauthorized Hardware
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-7.9.md
  relation: has_enhancement
  description: CM-7 has enhancement CM-7.9.
nist_id: CM-7
sort_id: cm-07
implementation_level: organization
parameter_ids:
- cm-7_prm_2
- cm-07_odp.01
- cm-07_odp.02
- cm-07_odp.03
- cm-07_odp.04
- cm-07_odp.05
- cm-07_odp.06
reference_links:
- '#678e3d6c-150b-4393-aec5-6e3481eb1e00'
- '#eea3c092-42ed-4382-a6f4-1adadef01b9d'
- '#7c37a38d-21d7-40d8-bc3d-b5e27eac17e1'
- '#a295ca19-8c75-4b4c-8800-98024732e181'
- '#38f39739-1ebd-43b1-8b8c-00f591d89ebd'
- '#ac-3'
- '#ac-4'
- '#cm-2'
- '#cm-5'
- '#cm-6'
- '#cm-11'
- '#ra-5'
- '#sa-4'
- '#sa-5'
- '#sa-8'
- '#sa-9'
- '#sa-15'
- '#sc-2'
- '#sc-3'
- '#sc-7'
- '#sc-37'
- '#si-4'
---

# Summary

SP 800-53 control CM-7.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Systems provide a wide variety of functions and services. Some of the functions and services routinely provided by default may not be necessary to support essential organizational missions, functions, or operations. Additionally, it is sometimes convenient to provide multiple services from a single system component, but doing so increases risk over limiting the services provided by that single component. Where feasible, organizations limit component functionality to a single function per component. Organizations consider removing unused or unnecessary software and disabling unused or unnecessary physical and logical ports and protocols to prevent unauthorized connection of components, transfer of information, and tunneling. Organizations employ network scanning tools, intrusion detection and prevention systems, and end-point protection technologies, such as firewalls and host-based intrusion detection systems, to identify and prevent the use of prohibited functions, protocols, ports, and services. Least functionality can also be achieved as part of the fundamental design and development of the system (see [SA-8](#sa-8), [SC-2](#sc-2) , and [SC-3](#sc-3)).

# Parameters

- `cm-7_prm_2`
- `cm-07_odp.01`
- `cm-07_odp.02`
- `cm-07_odp.03`
- `cm-07_odp.04`
- `cm-07_odp.05`
- `cm-07_odp.06`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
