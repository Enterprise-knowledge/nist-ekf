---
type: framework_subcategory
title: PR.PS-04
description: Log records are generated and made available for continuous monitoring
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
- pr-ps-04
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
nist_id: PR.PS-04
implementation_example_count: 3
---

# Summary

Log records are generated and made available for continuous monitoring

# Implementation Examples

- Configure all operating systems, applications, and services (including cloud-based services) to generate log records
- Configure log generators to securely share their logs with the organization's logging infrastructure systems and services
- Configure log generators to record the data needed by zero-trust architectures

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
