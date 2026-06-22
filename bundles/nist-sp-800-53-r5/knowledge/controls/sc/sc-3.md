---
type: control
title: SC-3 - Security Function Isolation
description: Isolate security functions from nonsecurity functions.
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
  description: SC-3 - Security Function Isolation is part of its parent SP 800-53 structure.
- name: SC-3.1 - Hardware Separation
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-3.1.md
  relation: has_enhancement
  description: SC-3 has enhancement SC-3.1.
- name: SC-3.2 - Access and Flow Control Functions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-3.2.md
  relation: has_enhancement
  description: SC-3 has enhancement SC-3.2.
- name: SC-3.3 - Minimize Nonsecurity Functionality
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-3.3.md
  relation: has_enhancement
  description: SC-3 has enhancement SC-3.3.
- name: SC-3.4 - Module Coupling and Cohesiveness
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-3.4.md
  relation: has_enhancement
  description: SC-3 has enhancement SC-3.4.
- name: SC-3.5 - Layered Structures
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-3.5.md
  relation: has_enhancement
  description: SC-3 has enhancement SC-3.5.
nist_id: SC-3
sort_id: sc-03
implementation_level: system
parameter_ids: []
reference_links:
- '#ac-3'
- '#ac-6'
- '#ac-25'
- '#cm-2'
- '#cm-4'
- '#sa-4'
- '#sa-5'
- '#sa-8'
- '#sa-15'
- '#sa-17'
- '#sc-2'
- '#sc-7'
- '#sc-32'
- '#sc-39'
- '#si-16'
---

# Summary

Isolate security functions from nonsecurity functions.

# Statement

Isolate security functions from nonsecurity functions.

# Guidance

Security functions are isolated from nonsecurity functions by means of an isolation boundary implemented within a system via partitions and domains. The isolation boundary controls access to and protects the integrity of the hardware, software, and firmware that perform system security functions. Systems implement code separation in many ways, such as through the provision of security kernels via processor rings or processor modes. For non-kernel code, security function isolation is often achieved through file system protections that protect the code on disk and address space protections that protect executing code. Systems can restrict access to security functions using access control mechanisms and by implementing least privilege capabilities. While the ideal is for all code within the defined security function isolation boundary to only contain security-relevant code, it is sometimes necessary to include nonsecurity functions as an exception. The isolation of security functions from nonsecurity functions can be achieved by applying the systems security engineering design principles in [SA-8](#sa-8) , including [SA-8(1)](#sa-8.1), [SA-8(3)](#sa-8.3), [SA-8(4)](#sa-8.4), [SA-8(10)](#sa-8.10), [SA-8(12)](#sa-8.12), [SA-8(13)](#sa-8.13), [SA-8(14)](#sa-8.14) , and [SA-8(18)](#sa-8.18).

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
