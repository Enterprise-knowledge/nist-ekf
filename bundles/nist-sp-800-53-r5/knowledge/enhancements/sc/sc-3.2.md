---
type: control_enhancement
title: SC-3.2 - Access and Flow Control Functions
description: Isolate security functions enforcing access and information flow control from nonsecurity functions
  and from other security functions.
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-3.md
  relation: part_of
  description: SC-3.2 - Access and Flow Control Functions is part of its parent SP 800-53 structure.
- name: SC-3 - Security Function Isolation
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-3.md
  relation: enhances
  description: SC-3.2 enhances base control SC-3.
nist_id: SC-3.2
sort_id: sc-03.02
implementation_level: system
parameter_ids: []
reference_links:
- '#sc-3'
---

# Summary

Isolate security functions enforcing access and information flow control from nonsecurity functions and from other security functions.

# Statement

Isolate security functions enforcing access and information flow control from nonsecurity functions and from other security functions.

# Guidance

Security function isolation occurs because of implementation. The functions can still be scanned and monitored. Security functions that are potentially isolated from access and flow control enforcement functions include auditing, intrusion detection, and malicious code protection functions.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
