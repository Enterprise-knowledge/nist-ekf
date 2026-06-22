---
type: control
title: CM-3 - Configuration Change Control
description: SP 800-53 control CM-3.
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
  description: CM-3 - Configuration Change Control is part of its parent SP 800-53 structure.
- name: CM-3.1 - Automated Documentation, Notification, and Prohibition of Changes
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-3.1.md
  relation: has_enhancement
  description: CM-3 has enhancement CM-3.1.
- name: CM-3.2 - Testing, Validation, and Documentation of Changes
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-3.2.md
  relation: has_enhancement
  description: CM-3 has enhancement CM-3.2.
- name: CM-3.3 - Automated Change Implementation
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-3.3.md
  relation: has_enhancement
  description: CM-3 has enhancement CM-3.3.
- name: CM-3.4 - Security and Privacy Representatives
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-3.4.md
  relation: has_enhancement
  description: CM-3 has enhancement CM-3.4.
- name: CM-3.5 - Automated Security Response
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-3.5.md
  relation: has_enhancement
  description: CM-3 has enhancement CM-3.5.
- name: CM-3.6 - Cryptography Management
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-3.6.md
  relation: has_enhancement
  description: CM-3 has enhancement CM-3.6.
- name: CM-3.7 - Review System Changes
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-3.7.md
  relation: has_enhancement
  description: CM-3 has enhancement CM-3.7.
- name: CM-3.8 - Prevent or Restrict Configuration Changes
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-3.8.md
  relation: has_enhancement
  description: CM-3 has enhancement CM-3.8.
nist_id: CM-3
sort_id: cm-03
implementation_level: organization
parameter_ids:
- cm-03_odp.01
- cm-03_odp.02
- cm-03_odp.03
- cm-03_odp.04
- cm-03_odp.05
reference_links:
- '#0f66be67-85e7-4ca6-bd19-39453e9f4394'
- '#20db4e66-e257-450c-b2e4-2bb9a62a2c88'
- '#98d415ca-7281-4064-9931-0c366637e324'
- '#ca-7'
- '#cm-2'
- '#cm-4'
- '#cm-5'
- '#cm-6'
- '#cm-9'
- '#cm-11'
- '#ia-3'
- '#ma-2'
- '#pe-16'
- '#pt-6'
- '#ra-8'
- '#sa-8'
- '#sa-10'
- '#sc-28'
- '#sc-34'
- '#sc-37'
- '#si-2'
- '#si-3'
- '#si-4'
- '#si-7'
- '#si-10'
- '#sr-11'
---

# Summary

SP 800-53 control CM-3.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Configuration change control for organizational systems involves the systematic proposal, justification, implementation, testing, review, and disposition of system changes, including system upgrades and modifications. Configuration change control includes changes to baseline configurations, configuration items of systems, operational procedures, configuration settings for system components, remediate vulnerabilities, and unscheduled or unauthorized changes. Processes for managing configuration changes to systems include Configuration Control Boards or Change Advisory Boards that review and approve proposed changes. For changes that impact privacy risk, the senior agency official for privacy updates privacy impact assessments and system of records notices. For new systems or major upgrades, organizations consider including representatives from the development organizations on the Configuration Control Boards or Change Advisory Boards. Auditing of changes includes activities before and after changes are made to systems and the auditing activities required to implement such changes. See also [SA-10](#sa-10).

# Parameters

- `cm-03_odp.01`
- `cm-03_odp.02`
- `cm-03_odp.03`
- `cm-03_odp.04`
- `cm-03_odp.05`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
