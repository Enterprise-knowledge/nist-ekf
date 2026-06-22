---
type: framework_subcategory
title: PR.AA-04
description: Identity assertions are protected, conveyed, and verified
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
- pr-aa-04
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
- name: Identity Management, Authentication, and Access Control
  path: /bundles/nist-csf-2/knowledge/categories/pr.aa.md
  relation: part_of
  description: This Subcategory is part of the PR.AA Category.
nist_id: PR.AA-04
implementation_example_count: 3
---

# Summary

Identity assertions are protected, conveyed, and verified

# Implementation Examples

- Protect identity assertions that are used to convey authentication and user information through single sign-on systems
- Protect identity assertions that are used to convey authentication and user information between federated systems
- Implement standards-based approaches for identity assertions in all contexts, and follow all guidance for the generation (e.g., data models, metadata), protection (e.g., digital signing, encryption), and verification (e.g., signature validation) of identity assertions

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
