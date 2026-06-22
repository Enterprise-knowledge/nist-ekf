---
type: framework_function
title: RC - Recover
description: Assets and operations affected by a cybersecurity incident are restored
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
- rc
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
- name: Incident Recovery Communication
  path: /bundles/nist-csf-2/knowledge/categories/rc.co.md
  relation: contains
  description: RC contains the RC.CO Category.
- name: Incident Recovery Plan Execution
  path: /bundles/nist-csf-2/knowledge/categories/rc.rp.md
  relation: contains
  description: RC contains the RC.RP Category.
nist_id: RC
---

# Summary

Assets and operations affected by a cybersecurity incident are restored

# Structure

This Function contains 2 Categories.

## Categories

- [RC.CO - Incident Recovery Communication](../categories/rc.co.md) - Restoration activities are coordinated with internal and external parties
- [RC.RP - Incident Recovery Plan Execution](../categories/rc.rp.md) - Restoration activities are performed to ensure operational availability of systems and services affected by cybersecurity incidents

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
