---
type: control_enhancement
title: CM-7.5 - Authorized Software — Allow-by-exception
description: SP 800-53 control CM-7.5.
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control-enhancement
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-7.md
  relation: part_of
  description: CM-7.5 - Authorized Software — Allow-by-exception is part of its parent SP 800-53 structure.
- name: CM-7 - Least Functionality
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-7.md
  relation: enhances
  description: CM-7.5 enhances base control CM-7.
nist_id: CM-7.5
sort_id: cm-07.05
implementation_level: organization
parameter_ids:
- cm-07.05_odp.01
- cm-07.05_odp.02
reference_links:
- '#cm-7'
- '#cm-2'
- '#cm-6'
- '#cm-8'
- '#cm-10'
- '#pl-9'
- '#pm-5'
- '#sa-10'
- '#sc-34'
- '#si-7'
---

# Summary

SP 800-53 control CM-7.5.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Authorized software programs can be limited to specific versions or from a specific source. To facilitate a comprehensive authorized software process and increase the strength of protection for attacks that bypass application level authorized software, software programs may be decomposed into and monitored at different levels of detail. These levels include applications, application programming interfaces, application modules, scripts, system processes, system services, kernel functions, registries, drivers, and dynamic link libraries. The concept of permitting the execution of authorized software may also be applied to user actions, system ports and protocols, IP addresses/ranges, websites, and MAC addresses. Organizations consider verifying the integrity of authorized software programs using digital signatures, cryptographic checksums, or hash functions. Verification of authorized software can occur either prior to execution or at system startup. The identification of authorized URLs for websites is addressed in [CA-3(5)](#ca-3.5) and [SC-7](#sc-7).

# Parameters

- `cm-07.05_odp.01`
- `cm-07.05_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
