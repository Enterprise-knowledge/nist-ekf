---
type: control
title: CM-9 - Configuration Management Plan
description: 'Develop, document, and implement a configuration management plan for the system that:'
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
  description: CM-9 - Configuration Management Plan is part of its parent SP 800-53 structure.
- name: CM-9.1 - Assignment of Responsibility
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-9.1.md
  relation: has_enhancement
  description: CM-9 has enhancement CM-9.1.
nist_id: CM-9
sort_id: cm-09
implementation_level: organization
parameter_ids:
- cm-09_odp
reference_links:
- '#20db4e66-e257-450c-b2e4-2bb9a62a2c88'
- '#cm-2'
- '#cm-3'
- '#cm-4'
- '#cm-5'
- '#cm-8'
- '#pl-2'
- '#ra-8'
- '#sa-10'
- '#si-12'
---

# Summary

Develop, document, and implement a configuration management plan for the system that:

# Statement

Develop, document, and implement a configuration management plan for the system that:

# Guidance

Configuration management activities occur throughout the system development life cycle. As such, there are developmental configuration management activities (e.g., the control of code and software libraries) and operational configuration management activities (e.g., control of installed components and how the components are configured). Configuration management plans satisfy the requirements in configuration management policies while being tailored to individual systems. Configuration management plans define processes and procedures for how configuration management is used to support system development life cycle activities.

Configuration management plans are generated during the development and acquisition stage of the system development life cycle. The plans describe how to advance changes through change management processes; update configuration settings and baselines; maintain component inventories; control development, test, and operational environments; and develop, release, and update key documents.

Organizations can employ templates to help ensure the consistent and timely development and implementation of configuration management plans. Templates can represent a configuration management plan for the organization with subsets of the plan implemented on a system by system basis. Configuration management approval processes include the designation of key stakeholders responsible for reviewing and approving proposed changes to systems, and personnel who conduct security and privacy impact analyses prior to the implementation of changes to the systems. Configuration items are the system components, such as the hardware, software, firmware, and documentation to be configuration-managed. As systems continue through the system development life cycle, new configuration items may be identified, and some existing configuration items may no longer need to be under configuration control.

# Parameters

- `cm-09_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
