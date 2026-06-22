---
type: framework_subcategory
title: PR.PS-02
description: Software is maintained, replaced, and removed commensurate with risk
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: cybersecurity-risk-management
system: nist-csf-2
tags:
- nist
- csf
- subcategory
- pr-ps-02
confidence: high
review:
  status: agent-generated
  reviewed_by: EKF generation workflow
  reviewed_at: '2026-06-22T00:00:00Z'
sources:
- name: NIST CSF 2.0 PDF
  path: /source/NIST.CSWP.29.pdf
  kind: pdf
  description: Local source PDF for CSF 2.0.
- name: CSF Reference Tool export
  path: /artifacts/data/csf-2.0-export.xlsx
  kind: xlsx
  description: NIST CSF Reference Tool export used for Categories, Subcategories, and Implementation Examples.
related:
- name: Platform Security
  path: /bundles/nist-csf-2/knowledge/categories/pr.ps.md
  relation: part_of
  description: This Subcategory is part of the PR.PS Category.
nist_id: PR.PS-02
implementation_example_count: 6
---

# Summary

Software is maintained, replaced, and removed commensurate with risk

# Implementation Examples

- Perform routine and emergency patching within the timeframes specified in the vulnerability management plan
- Update container images, and deploy new container instances to replace rather than update existing instances
- Replace end-of-life software and service versions with supported, maintained versions
- Uninstall and remove unauthorized software and services that pose undue risks
- Uninstall and remove any unnecessary software components (e.g., operating system utilities) that attackers might misuse
- Define and implement plans for software and service end-of-life maintenance support and obsolescence

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
