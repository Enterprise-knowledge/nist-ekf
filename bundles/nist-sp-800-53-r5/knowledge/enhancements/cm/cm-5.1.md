---
type: control_enhancement
title: CM-5.1 - Automated Access Enforcement and Audit Records
description: SP 800-53 control CM-5.1.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-5.md
  relation: part_of
  description: CM-5.1 - Automated Access Enforcement and Audit Records is part of its parent SP 800-53 structure.
- name: CM-5 - Access Restrictions for Change
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-5.md
  relation: enhances
  description: CM-5.1 enhances base control CM-5.
nist_id: CM-5.1
sort_id: cm-05.01
implementation_level: system
parameter_ids:
- cm-05.01_odp
reference_links:
- '#cm-5'
- '#au-2'
- '#au-6'
- '#au-7'
- '#au-12'
- '#cm-6'
- '#cm-11'
- '#si-12'
---

# Summary

SP 800-53 control CM-5.1.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Organizations log system accesses associated with applying configuration changes to ensure that configuration change control is implemented and to support after-the-fact actions should organizations discover any unauthorized changes.

# Parameters

- `cm-05.01_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
