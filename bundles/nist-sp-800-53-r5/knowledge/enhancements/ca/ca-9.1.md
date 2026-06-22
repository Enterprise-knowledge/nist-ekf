---
type: control_enhancement
title: CA-9.1 - Compliance Checks
description: Perform security and privacy compliance checks on constituent system components prior to the establishment
  of the internal connection.
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
- ca
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ca/ca-9.md
  relation: part_of
  description: CA-9.1 - Compliance Checks is part of its parent SP 800-53 structure.
- name: CA-9 - Internal System Connections
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ca/ca-9.md
  relation: enhances
  description: CA-9.1 enhances base control CA-9.
nist_id: CA-9.1
sort_id: ca-09.01
implementation_level: organization
parameter_ids: []
reference_links:
- '#ca-9'
- '#cm-6'
---

# Summary

Perform security and privacy compliance checks on constituent system components prior to the establishment of the internal connection.

# Statement

Perform security and privacy compliance checks on constituent system components prior to the establishment of the internal connection.

# Guidance

Compliance checks include verification of the relevant baseline configuration.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
