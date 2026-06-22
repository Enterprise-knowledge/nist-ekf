---
type: control_enhancement
title: CM-2.6 - Development and Test Environments
description: Maintain a baseline configuration for system development and test environments that is managed separately
  from the operational baseline configuration.
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-2.md
  relation: part_of
  description: CM-2.6 - Development and Test Environments is part of its parent SP 800-53 structure.
- name: CM-2 - Baseline Configuration
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-2.md
  relation: enhances
  description: CM-2.6 enhances base control CM-2.
nist_id: CM-2.6
sort_id: cm-02.06
implementation_level: organization
parameter_ids: []
reference_links:
- '#cm-2'
- '#cm-4'
- '#sc-3'
- '#sc-7'
---

# Summary

Maintain a baseline configuration for system development and test environments that is managed separately from the operational baseline configuration.

# Statement

Maintain a baseline configuration for system development and test environments that is managed separately from the operational baseline configuration.

# Guidance

Establishing separate baseline configurations for development, testing, and operational environments protects systems from unplanned or unexpected events related to development and testing activities. Separate baseline configurations allow organizations to apply the configuration management that is most appropriate for each type of configuration. For example, the management of operational configurations typically emphasizes the need for stability, while the management of development or test configurations requires greater flexibility. Configurations in the test environment mirror configurations in the operational environment to the extent practicable so that the results of the testing are representative of the proposed changes to the operational systems. Separate baseline configurations do not necessarily require separate physical environments.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
