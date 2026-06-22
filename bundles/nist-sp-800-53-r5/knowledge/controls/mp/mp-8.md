---
type: control
title: MP-8 - Media Downgrading
description: SP 800-53 control MP-8.
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
- mp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/mp.md
  relation: part_of
  description: MP-8 - Media Downgrading is part of its parent SP 800-53 structure.
- name: MP-8.1 - Documentation of Process
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-8.1.md
  relation: has_enhancement
  description: MP-8 has enhancement MP-8.1.
- name: MP-8.2 - Equipment Testing
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-8.2.md
  relation: has_enhancement
  description: MP-8 has enhancement MP-8.2.
- name: MP-8.3 - Controlled Unclassified Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-8.3.md
  relation: has_enhancement
  description: MP-8 has enhancement MP-8.3.
- name: MP-8.4 - Classified Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-8.4.md
  relation: has_enhancement
  description: MP-8 has enhancement MP-8.4.
nist_id: MP-8
sort_id: mp-08
implementation_level: organization
parameter_ids:
- mp-08_odp.01
- mp-08_odp.02
reference_links:
- '#91f992fb-f668-4c91-a50f-0f05b95ccee3'
- '#df9f87e9-71e7-4c74-9ac3-3cabd4e92f21'
---

# Summary

SP 800-53 control MP-8.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Media downgrading applies to digital and non-digital media subject to release outside of the organization, whether the media is considered removable or not. When applied to system media, the downgrading process removes information from the media, typically by security category or classification level, such that the information cannot be retrieved or reconstructed. Downgrading of media includes redacting information to enable wider release and distribution. Downgrading ensures that empty space on the media is devoid of information.

# Parameters

- `mp-08_odp.01`
- `mp-08_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
