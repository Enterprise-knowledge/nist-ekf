---
type: framework_subcategory
title: ID.AM-07
description: Inventories of data and corresponding metadata for designated data types are maintained
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
- id-am-07
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
- name: Asset Management
  path: /bundles/nist-csf-2/knowledge/categories/id.am.md
  relation: part_of
  description: This Subcategory is part of the ID.AM Category.
nist_id: ID.AM-07
implementation_example_count: 4
---

# Summary

Inventories of data and corresponding metadata for designated data types are maintained

# Implementation Examples

- Maintain a list of the designated data types of interest (e.g., personally identifiable information, protected health information, financial account numbers, organization intellectual property, operational technology data)
- Continuously discover and analyze ad hoc data to identify new instances of designated data types
- Assign data classifications to designated data types through tags or labels
- Track the provenance, data owner, and geolocation of each instance of designated data types

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
