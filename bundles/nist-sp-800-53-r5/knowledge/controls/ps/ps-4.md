---
type: control
title: PS-4 - Personnel Termination
description: 'Upon termination of individual employment:'
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
- ps
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ps.md
  relation: part_of
  description: PS-4 - Personnel Termination is part of its parent SP 800-53 structure.
- name: PS-4.1 - Post-employment Requirements
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ps/ps-4.1.md
  relation: has_enhancement
  description: PS-4 has enhancement PS-4.1.
- name: PS-4.2 - Automated Actions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ps/ps-4.2.md
  relation: has_enhancement
  description: PS-4 has enhancement PS-4.2.
nist_id: PS-4
sort_id: ps-04
implementation_level: organization
parameter_ids:
- ps-04_odp.01
- ps-04_odp.02
reference_links:
- '#ac-2'
- '#ia-4'
- '#pe-2'
- '#pm-12'
- '#ps-6'
- '#ps-7'
---

# Summary

Upon termination of individual employment:

# Statement

Upon termination of individual employment:

# Guidance

System property includes hardware authentication tokens, system administration technical manuals, keys, identification cards, and building passes. Exit interviews ensure that terminated individuals understand the security constraints imposed by being former employees and that proper accountability is achieved for system-related property. Security topics at exit interviews include reminding individuals of nondisclosure agreements and potential limitations on future employment. Exit interviews may not always be possible for some individuals, including in cases related to the unavailability of supervisors, illnesses, or job abandonment. Exit interviews are important for individuals with security clearances. The timely execution of termination actions is essential for individuals who have been terminated for cause. In certain situations, organizations consider disabling the system accounts of individuals who are being terminated prior to the individuals being notified.

# Parameters

- `ps-04_odp.01`
- `ps-04_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
