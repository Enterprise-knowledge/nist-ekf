---
type: control
title: CM-2 - Baseline Configuration
description: SP 800-53 control CM-2.
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
  description: CM-2 - Baseline Configuration is part of its parent SP 800-53 structure.
- name: CM-2.1 - Reviews and Updates
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-2.1.md
  relation: has_enhancement
  description: CM-2 has enhancement CM-2.1.
- name: CM-2.2 - Automation Support for Accuracy and Currency
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-2.2.md
  relation: has_enhancement
  description: CM-2 has enhancement CM-2.2.
- name: CM-2.3 - Retention of Previous Configurations
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-2.3.md
  relation: has_enhancement
  description: CM-2 has enhancement CM-2.3.
- name: CM-2.4 - Unauthorized Software
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-2.4.md
  relation: has_enhancement
  description: CM-2 has enhancement CM-2.4.
- name: CM-2.5 - Authorized Software
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-2.5.md
  relation: has_enhancement
  description: CM-2 has enhancement CM-2.5.
- name: CM-2.6 - Development and Test Environments
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-2.6.md
  relation: has_enhancement
  description: CM-2 has enhancement CM-2.6.
- name: CM-2.7 - Configure Systems and Components for High-risk Areas
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/cm/cm-2.7.md
  relation: has_enhancement
  description: CM-2 has enhancement CM-2.7.
nist_id: CM-2
sort_id: cm-02
implementation_level: organization
parameter_ids:
- cm-02_odp.01
- cm-02_odp.02
reference_links:
- '#0f66be67-85e7-4ca6-bd19-39453e9f4394'
- '#20db4e66-e257-450c-b2e4-2bb9a62a2c88'
- '#ac-19'
- '#au-6'
- '#ca-9'
- '#cm-1'
- '#cm-3'
- '#cm-5'
- '#cm-6'
- '#cm-8'
- '#cm-9'
- '#cp-9'
- '#cp-10'
- '#cp-12'
- '#ma-2'
- '#pl-8'
- '#pm-5'
- '#sa-8'
- '#sa-10'
- '#sa-15'
- '#sc-18'
---

# Summary

SP 800-53 control CM-2.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Baseline configurations for systems and system components include connectivity, operational, and communications aspects of systems. Baseline configurations are documented, formally reviewed, and agreed-upon specifications for systems or configuration items within those systems. Baseline configurations serve as a basis for future builds, releases, or changes to systems and include security and privacy control implementations, operational procedures, information about system components, network topology, and logical placement of components in the system architecture. Maintaining baseline configurations requires creating new baselines as organizational systems change over time. Baseline configurations of systems reflect the current enterprise architecture.

# Parameters

- `cm-02_odp.01`
- `cm-02_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
