---
type: framework_function
title: ID - Identify
description: The organization's current cybersecurity risks are understood
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: cybersecurity-risk-management
system: nist-csf-2
tags:
- nist
- csf
- function
- id
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
- name: CSF Core
  path: /bundles/nist-csf-2/knowledge/core/csf-core.md
  relation: part_of
  description: This Function is part of the CSF Core.
- name: Asset Management
  path: /bundles/nist-csf-2/knowledge/categories/id.am.md
  relation: contains
  description: ID contains the ID.AM Category.
- name: Improvement
  path: /bundles/nist-csf-2/knowledge/categories/id.im.md
  relation: contains
  description: ID contains the ID.IM Category.
- name: Risk Assessment
  path: /bundles/nist-csf-2/knowledge/categories/id.ra.md
  relation: contains
  description: ID contains the ID.RA Category.
nist_id: ID
---

# Summary

The organization's current cybersecurity risks are understood

# Structure

This Function contains 3 Categories.

## Categories

- [ID.AM - Asset Management](../categories/id.am.md) - Assets (e.g., data, hardware, software, systems, facilities, services, people) that enable the organization to achieve business purposes are identified and managed consistent with their relative importance to organizational objectives and the organization's risk strategy
- [ID.IM - Improvement](../categories/id.im.md) - Improvements to organizational cybersecurity risk management processes, procedures and activities are identified across all CSF Functions
- [ID.RA - Risk Assessment](../categories/id.ra.md) - The cybersecurity risk to the organization, assets, and individuals is understood by the organization

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
