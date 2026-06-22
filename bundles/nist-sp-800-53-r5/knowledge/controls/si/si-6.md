---
type: control
title: SI-6 - Security and Privacy Function Verification
description: SP 800-53 control SI-6.
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
- si
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/si.md
  relation: part_of
  description: SI-6 - Security and Privacy Function Verification is part of its parent SP 800-53 structure.
- name: SI-6.1 - Notification of Failed Security Tests
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-6.1.md
  relation: has_enhancement
  description: SI-6 has enhancement SI-6.1.
- name: SI-6.2 - Automation Support for Distributed Testing
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-6.2.md
  relation: has_enhancement
  description: SI-6 has enhancement SI-6.2.
- name: SI-6.3 - Report Verification Results
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-6.3.md
  relation: has_enhancement
  description: SI-6 has enhancement SI-6.3.
nist_id: SI-6
sort_id: si-06
implementation_level: system
parameter_ids:
- si-6_prm_1
- si-06_odp.01
- si-06_odp.02
- si-06_odp.03
- si-06_odp.04
- si-06_odp.05
- si-06_odp.06
- si-06_odp.07
- si-06_odp.08
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#ca-7'
- '#cm-4'
- '#cm-6'
- '#si-7'
---

# Summary

SP 800-53 control SI-6.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Transitional states for systems include system startup, restart, shutdown, and abort. System notifications include hardware indicator lights, electronic alerts to system administrators, and messages to local computer consoles. In contrast to security function verification, privacy function verification ensures that privacy functions operate as expected and are approved by the senior agency official for privacy or that privacy attributes are applied or used as expected.

# Parameters

- `si-6_prm_1`
- `si-06_odp.01`
- `si-06_odp.02`
- `si-06_odp.03`
- `si-06_odp.04`
- `si-06_odp.05`
- `si-06_odp.06`
- `si-06_odp.07`
- `si-06_odp.08`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
