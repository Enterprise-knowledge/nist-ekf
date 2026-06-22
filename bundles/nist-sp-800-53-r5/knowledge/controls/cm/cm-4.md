---
type: control
title: CM-4 - Impact Analyses
description: Analyze changes to the system to determine potential security and privacy impacts prior to change implementation.
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/cm.md
  relation: part_of
  description: CM-4 - Impact Analyses is part of its parent SP 800-53 structure.
- name: CM-4.1 - Separate Test Environments
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-4.1.md
  relation: has_enhancement
  description: CM-4 has enhancement CM-4.1.
- name: CM-4.2 - Verification of Controls
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-4.2.md
  relation: has_enhancement
  description: CM-4 has enhancement CM-4.2.
nist_id: CM-4
sort_id: cm-04
implementation_level: organization
parameter_ids: []
reference_links:
- '#20db4e66-e257-450c-b2e4-2bb9a62a2c88'
- '#ca-7'
- '#cm-3'
- '#cm-8'
- '#cm-9'
- '#ma-2'
- '#ra-3'
- '#ra-5'
- '#ra-8'
- '#sa-5'
- '#sa-8'
- '#sa-10'
- '#si-2'
---

# Summary

Analyze changes to the system to determine potential security and privacy impacts prior to change implementation.

# Statement

Analyze changes to the system to determine potential security and privacy impacts prior to change implementation.

# Guidance

Organizational personnel with security or privacy responsibilities conduct impact analyses. Individuals conducting impact analyses possess the necessary skills and technical expertise to analyze the changes to systems as well as the security or privacy ramifications. Impact analyses include reviewing security and privacy plans, policies, and procedures to understand control requirements; reviewing system design documentation and operational procedures to understand control implementation and how specific system changes might affect the controls; reviewing the impact of changes on organizational supply chain partners with stakeholders; and determining how potential changes to a system create new risks to the privacy of individuals and the ability of implemented controls to mitigate those risks. Impact analyses also include risk assessments to understand the impact of the changes and determine if additional controls are required.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
