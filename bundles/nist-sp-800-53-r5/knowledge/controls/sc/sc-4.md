---
type: control
title: SC-4 - Information in Shared System Resources
description: Prevent unauthorized and unintended information transfer via shared system resources.
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
  description: SC-4 - Information in Shared System Resources is part of its parent SP 800-53 structure.
- name: SC-4.1 - Security Levels
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-4.1.md
  relation: has_enhancement
  description: SC-4 has enhancement SC-4.1.
- name: SC-4.2 - Multilevel or Periods Processing
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-4.2.md
  relation: has_enhancement
  description: SC-4 has enhancement SC-4.2.
nist_id: SC-4
sort_id: sc-04
implementation_level: system
parameter_ids: []
reference_links:
- '#ac-3'
- '#ac-4'
- '#sa-8'
---

# Summary

Prevent unauthorized and unintended information transfer via shared system resources.

# Statement

Prevent unauthorized and unintended information transfer via shared system resources.

# Guidance

Preventing unauthorized and unintended information transfer via shared system resources stops information produced by the actions of prior users or roles (or the actions of processes acting on behalf of prior users or roles) from being available to current users or roles (or current processes acting on behalf of current users or roles) that obtain access to shared system resources after those resources have been released back to the system. Information in shared system resources also applies to encrypted representations of information. In other contexts, control of information in shared system resources is referred to as object reuse and residual information protection. Information in shared system resources does not address information remanence, which refers to the residual representation of data that has been nominally deleted; covert channels (including storage and timing channels), where shared system resources are manipulated to violate information flow restrictions; or components within systems for which there are only single users or roles.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
