---
type: framework_subcategory
title: PR.DS-11
description: Backups of data are created, protected, maintained, and tested
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
- pr-ds-11
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
nist_id: PR.DS-11
implementation_example_count: 4
---

# Summary

Backups of data are created, protected, maintained, and tested

# Implementation Examples

- Continuously back up critical data in near-real-time, and back up other data frequently at agreed-upon schedules
- Test backups and restores for all types of data sources at least annually
- Securely store some backups offline and offsite so that an incident or disaster will not damage them
- Enforce geographic separation and geolocation restrictions for data backup storage

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
