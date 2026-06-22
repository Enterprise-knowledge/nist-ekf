---
type: control_enhancement
title: CP-6.1 - Separation from Primary Site
description: Identify an alternate storage site that is sufficiently separated from the primary storage site to
  reduce susceptibility to the same threats.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-6.md
  relation: part_of
  description: CP-6.1 - Separation from Primary Site is part of its parent SP 800-53 structure.
- name: CP-6 - Alternate Storage Site
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-6.md
  relation: enhances
  description: CP-6.1 enhances base control CP-6.
nist_id: CP-6.1
sort_id: cp-06.01
implementation_level: organization
parameter_ids: []
reference_links:
- '#cp-6'
- '#ra-3'
---

# Summary

Identify an alternate storage site that is sufficiently separated from the primary storage site to reduce susceptibility to the same threats.

# Statement

Identify an alternate storage site that is sufficiently separated from the primary storage site to reduce susceptibility to the same threats.

# Guidance

Threats that affect alternate storage sites are defined in organizational risk assessments and include natural disasters, structural failures, hostile attacks, and errors of omission or commission. Organizations determine what is considered a sufficient degree of separation between primary and alternate storage sites based on the types of threats that are of concern. For threats such as hostile attacks, the degree of separation between sites is less relevant.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
