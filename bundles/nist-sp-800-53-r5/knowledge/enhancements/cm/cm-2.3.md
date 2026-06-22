---
type: control_enhancement
title: CM-2.3 - Retention of Previous Configurations
description: 'Retain {{ insert: param, cm-02.03_odp }} of previous versions of baseline configurations of the system
  to support rollback.'
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
  description: CM-2.3 - Retention of Previous Configurations is part of its parent SP 800-53 structure.
- name: CM-2 - Baseline Configuration
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-2.md
  relation: enhances
  description: CM-2.3 enhances base control CM-2.
nist_id: CM-2.3
sort_id: cm-02.03
implementation_level: organization
parameter_ids:
- cm-02.03_odp
reference_links:
- '#cm-2'
---

# Summary

Retain {{ insert: param, cm-02.03_odp }} of previous versions of baseline configurations of the system to support rollback.

# Statement

Retain {{ insert: param, cm-02.03_odp }} of previous versions of baseline configurations of the system to support rollback.

# Guidance

Retaining previous versions of baseline configurations to support rollback include hardware, software, firmware, configuration files, configuration records, and associated documentation.

# Parameters

- `cm-02.03_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
