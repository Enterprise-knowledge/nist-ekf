---
type: framework_subcategory
title: PR.DS-10
description: The confidentiality, integrity, and availability of data-in-use are protected
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
- pr-ds-10
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
- name: Data Security
  path: /bundles/nist-csf-2/knowledge/categories/pr.ds.md
  relation: part_of
  description: This Subcategory is part of the PR.DS Category.
nist_id: PR.DS-10
implementation_example_count: 2
---

# Summary

The confidentiality, integrity, and availability of data-in-use are protected

# Implementation Examples

- Remove data that must remain confidential (e.g., from processors and memory) as soon as it is no longer needed
- Protect data in use from access by other users and processes of the same platform

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
