---
type: control_enhancement
title: CM-7.7 - Code Execution in Protected Environments
description: 'Allow execution of binary or machine-executable code only in confined physical or virtual machine
  environments and with the explicit approval of {{ insert: param, cm-07.07_odp }} when such code is:'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-7.md
  relation: part_of
  description: CM-7.7 - Code Execution in Protected Environments is part of its parent SP 800-53 structure.
- name: CM-7 - Least Functionality
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-7.md
  relation: enhances
  description: CM-7.7 enhances base control CM-7.
nist_id: CM-7.7
sort_id: cm-07.07
implementation_level: organization
parameter_ids:
- cm-07.07_odp
reference_links:
- '#cm-7'
- '#cm-10'
- '#sc-44'
---

# Summary

Allow execution of binary or machine-executable code only in confined physical or virtual machine environments and with the explicit approval of {{ insert: param, cm-07.07_odp }} when such code is:

# Statement

Allow execution of binary or machine-executable code only in confined physical or virtual machine environments and with the explicit approval of {{ insert: param, cm-07.07_odp }} when such code is:

# Guidance

Code execution in protected environments applies to all sources of binary or machine-executable code, including commercial software and firmware and open-source software.

# Parameters

- `cm-07.07_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
