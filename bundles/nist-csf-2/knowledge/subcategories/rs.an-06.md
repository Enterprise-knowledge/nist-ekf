---
type: framework_subcategory
title: RS.AN-06
description: Actions performed during an investigation are recorded, and the records' integrity and provenance are
  preserved
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
- rs-an-06
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
- name: Incident Analysis
  path: /bundles/nist-csf-2/knowledge/categories/rs.an.md
  relation: part_of
  description: This Subcategory is part of the RS.AN Category.
nist_id: RS.AN-06
implementation_example_count: 2
---

# Summary

Actions performed during an investigation are recorded, and the records' integrity and provenance are preserved

# Implementation Examples

- Require each incident responder and others (e.g., system administrators, cybersecurity engineers) who perform incident response tasks to record their actions and make the record immutable
- Require the incident lead to document the incident in detail and be responsible for preserving the integrity of the documentation and the sources of all information being reported

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
