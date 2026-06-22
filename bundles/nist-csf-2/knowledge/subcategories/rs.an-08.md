---
type: framework_subcategory
title: RS.AN-08
description: An incident's magnitude is estimated and validated
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
- rs-an-08
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
nist_id: RS.AN-08
implementation_example_count: 2
---

# Summary

An incident's magnitude is estimated and validated

# Implementation Examples

- Review other potential targets of the incident to search for indicators of compromise and evidence of persistence
- Automatically run tools on targets to look for indicators of compromise and evidence of persistence

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
