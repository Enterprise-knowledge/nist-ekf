---
type: framework_subcategory
title: ID.AM-02
description: Inventories of software, services, and systems managed by the organization are maintained
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
- id-am-02
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
nist_id: ID.AM-02
implementation_example_count: 3
---

# Summary

Inventories of software, services, and systems managed by the organization are maintained

# Implementation Examples

- Maintain inventories for all types of software and services, including commercial-off-the-shelf, open-source, custom applications, API services, and cloud-based applications and services
- Constantly monitor all platforms, including containers and virtual machines, for software and service inventory changes
- Maintain an inventory of the organization's systems

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
