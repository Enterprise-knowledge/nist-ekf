---
type: control_enhancement
title: CP-8.2 - Single Points of Failure
description: Obtain alternate telecommunications services to reduce the likelihood of sharing a single point of
  failure with primary telecommunications services.
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-8.md
  relation: part_of
  description: CP-8.2 - Single Points of Failure is part of its parent SP 800-53 structure.
- name: CP-8 - Telecommunications Services
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-8.md
  relation: enhances
  description: CP-8.2 enhances base control CP-8.
nist_id: CP-8.2
sort_id: cp-08.02
implementation_level: organization
parameter_ids: []
reference_links:
- '#cp-8'
---

# Summary

Obtain alternate telecommunications services to reduce the likelihood of sharing a single point of failure with primary telecommunications services.

# Statement

Obtain alternate telecommunications services to reduce the likelihood of sharing a single point of failure with primary telecommunications services.

# Guidance

In certain circumstances, telecommunications service providers or services may share the same physical lines, which increases the vulnerability of a single failure point. It is important to have provider transparency for the actual physical transmission capability for telecommunication services.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
