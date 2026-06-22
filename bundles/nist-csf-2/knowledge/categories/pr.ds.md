---
type: framework_category
title: PR.DS - Data Security
description: Data are managed consistent with the organization's risk strategy to protect the confidentiality, integrity,
  and availability of information
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: cybersecurity-risk-management
system: nist-csf-2
tags:
- nist
- csf
- category
- pr
- pr-ds
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
- name: PROTECT
  path: /bundles/nist-csf-2/knowledge/functions/pr.md
  relation: part_of
  description: This Category is part of the PR Function.
- name: PR.DS-01
  path: /bundles/nist-csf-2/knowledge/subcategories/pr.ds-01.md
  relation: contains
  description: PR.DS contains Subcategory PR.DS-01.
- name: PR.DS-02
  path: /bundles/nist-csf-2/knowledge/subcategories/pr.ds-02.md
  relation: contains
  description: PR.DS contains Subcategory PR.DS-02.
- name: PR.DS-10
  path: /bundles/nist-csf-2/knowledge/subcategories/pr.ds-10.md
  relation: contains
  description: PR.DS contains Subcategory PR.DS-10.
- name: PR.DS-11
  path: /bundles/nist-csf-2/knowledge/subcategories/pr.ds-11.md
  relation: contains
  description: PR.DS contains Subcategory PR.DS-11.
nist_id: PR.DS
---

# Summary

Data are managed consistent with the organization's risk strategy to protect the confidentiality, integrity, and availability of information

# Structure

This Category is part of `PR` and contains 4 active Subcategories.

## Subcategories

- [PR.DS-01](../subcategories/pr.ds-01.md) - The confidentiality, integrity, and availability of data-at-rest are protected
- [PR.DS-02](../subcategories/pr.ds-02.md) - The confidentiality, integrity, and availability of data-in-transit are protected
- [PR.DS-10](../subcategories/pr.ds-10.md) - The confidentiality, integrity, and availability of data-in-use are protected
- [PR.DS-11](../subcategories/pr.ds-11.md) - Backups of data are created, protected, maintained, and tested

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
