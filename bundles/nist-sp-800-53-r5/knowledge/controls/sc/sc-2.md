---
type: control
title: SC-2 - Separation of System and User Functionality
description: Separate user functionality, including user interface services, from system management functionality.
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
- sc
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/sc.md
  relation: part_of
  description: SC-2 - Separation of System and User Functionality is part of its parent SP 800-53 structure.
- name: SC-2.1 - Interfaces for Non-privileged Users
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-2.1.md
  relation: has_enhancement
  description: SC-2 has enhancement SC-2.1.
- name: SC-2.2 - Disassociability
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-2.2.md
  relation: has_enhancement
  description: SC-2 has enhancement SC-2.2.
nist_id: SC-2
sort_id: sc-02
implementation_level: system
parameter_ids: []
reference_links:
- '#ac-6'
- '#sa-4'
- '#sa-8'
- '#sc-3'
- '#sc-7'
- '#sc-22'
- '#sc-32'
- '#sc-39'
---

# Summary

Separate user functionality, including user interface services, from system management functionality.

# Statement

Separate user functionality, including user interface services, from system management functionality.

# Guidance

System management functionality includes functions that are necessary to administer databases, network components, workstations, or servers. These functions typically require privileged user access. The separation of user functions from system management functions is physical or logical. Organizations may separate system management functions from user functions by using different computers, instances of operating systems, central processing units, or network addresses; by employing virtualization techniques; or some combination of these or other methods. Separation of system management functions from user functions includes web administrative interfaces that employ separate authentication methods for users of any other system resources. Separation of system and user functions may include isolating administrative interfaces on different domains and with additional access controls. The separation of system and user functionality can be achieved by applying the systems security engineering design principles in [SA-8](#sa-8) , including [SA-8(1)](#sa-8.1), [SA-8(3)](#sa-8.3), [SA-8(4)](#sa-8.4), [SA-8(10)](#sa-8.10), [SA-8(12)](#sa-8.12), [SA-8(13)](#sa-8.13), [SA-8(14)](#sa-8.14) , and [SA-8(18)](#sa-8.18).

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
