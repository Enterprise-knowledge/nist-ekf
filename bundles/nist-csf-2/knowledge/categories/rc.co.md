---
type: framework_category
title: RC.CO - Incident Recovery Communication
description: Restoration activities are coordinated with internal and external parties
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
- rc
- rc-co
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
- name: RECOVER
  path: /bundles/nist-csf-2/knowledge/functions/rc.md
  relation: part_of
  description: This Category is part of the RC Function.
- name: RC.CO-03
  path: /bundles/nist-csf-2/knowledge/subcategories/rc.co-03.md
  relation: contains
  description: RC.CO contains Subcategory RC.CO-03.
- name: RC.CO-04
  path: /bundles/nist-csf-2/knowledge/subcategories/rc.co-04.md
  relation: contains
  description: RC.CO contains Subcategory RC.CO-04.
nist_id: RC.CO
---

# Summary

Restoration activities are coordinated with internal and external parties

# Structure

This Category is part of `RC` and contains 2 active Subcategories.

## Subcategories

- [RC.CO-03](../subcategories/rc.co-03.md) - Recovery activities and progress in restoring operational capabilities are communicated to designated internal and external stakeholders
- [RC.CO-04](../subcategories/rc.co-04.md) - Public updates on incident recovery are shared using approved methods and messaging

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
