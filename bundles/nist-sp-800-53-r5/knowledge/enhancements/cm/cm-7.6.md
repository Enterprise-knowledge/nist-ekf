---
type: control_enhancement
title: CM-7.6 - Confined Environments with Limited Privileges
description: 'Require that the following user-installed software execute in a confined physical or virtual machine
  environment with limited privileges: {{ insert: param, cm-07.06_odp }}.'
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
  description: CM-7.6 - Confined Environments with Limited Privileges is part of its parent SP 800-53 structure.
- name: CM-7 - Least Functionality
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-7.md
  relation: enhances
  description: CM-7.6 enhances base control CM-7.
nist_id: CM-7.6
sort_id: cm-07.06
implementation_level: organization
parameter_ids:
- cm-07.06_odp
reference_links:
- '#cm-7'
- '#cm-11'
- '#sc-44'
---

# Summary

Require that the following user-installed software execute in a confined physical or virtual machine environment with limited privileges: {{ insert: param, cm-07.06_odp }}.

# Statement

Require that the following user-installed software execute in a confined physical or virtual machine environment with limited privileges: {{ insert: param, cm-07.06_odp }}.

# Guidance

Organizations identify software that may be of concern regarding its origin or potential for containing malicious code. For this type of software, user installations occur in confined environments of operation to limit or contain damage from malicious code that may be executed.

# Parameters

- `cm-07.06_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
