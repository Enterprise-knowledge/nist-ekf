---
type: framework_subcategory
title: PR.PS-05
description: Installation and execution of unauthorized software are prevented
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
- pr-ps-05
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
nist_id: PR.PS-05
implementation_example_count: 4
---

# Summary

Installation and execution of unauthorized software are prevented

# Implementation Examples

- When risk warrants it, restrict software execution to permitted products only or deny the execution of prohibited and unauthorized software
- Verify the source of new software and the software's integrity before installing it
- Configure platforms to use only approved DNS services that block access to known malicious domains
- Configure platforms to allow the installation of organization-approved software only

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
