---
type: framework_category
title: RC.RP - Incident Recovery Plan Execution
description: Restoration activities are performed to ensure operational availability of systems and services affected
  by cybersecurity incidents
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
- rc-rp
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
- name: RC.RP-01
  path: /bundles/nist-csf-2/knowledge/subcategories/rc.rp-01.md
  relation: contains
  description: RC.RP contains Subcategory RC.RP-01.
- name: RC.RP-02
  path: /bundles/nist-csf-2/knowledge/subcategories/rc.rp-02.md
  relation: contains
  description: RC.RP contains Subcategory RC.RP-02.
- name: RC.RP-03
  path: /bundles/nist-csf-2/knowledge/subcategories/rc.rp-03.md
  relation: contains
  description: RC.RP contains Subcategory RC.RP-03.
- name: RC.RP-04
  path: /bundles/nist-csf-2/knowledge/subcategories/rc.rp-04.md
  relation: contains
  description: RC.RP contains Subcategory RC.RP-04.
- name: RC.RP-05
  path: /bundles/nist-csf-2/knowledge/subcategories/rc.rp-05.md
  relation: contains
  description: RC.RP contains Subcategory RC.RP-05.
- name: RC.RP-06
  path: /bundles/nist-csf-2/knowledge/subcategories/rc.rp-06.md
  relation: contains
  description: RC.RP contains Subcategory RC.RP-06.
nist_id: RC.RP
---

# Summary

Restoration activities are performed to ensure operational availability of systems and services affected by cybersecurity incidents

# Structure

This Category is part of `RC` and contains 6 active Subcategories.

## Subcategories

- [RC.RP-01](../subcategories/rc.rp-01.md) - The recovery portion of the incident response plan is executed once initiated from the incident response process
- [RC.RP-02](../subcategories/rc.rp-02.md) - Recovery actions are selected, scoped, prioritized, and performed
- [RC.RP-03](../subcategories/rc.rp-03.md) - The integrity of backups and other restoration assets is verified before using them for restoration
- [RC.RP-04](../subcategories/rc.rp-04.md) - Critical mission functions and cybersecurity risk management are considered to establish post-incident operational norms
- [RC.RP-05](../subcategories/rc.rp-05.md) - The integrity of restored assets is verified, systems and services are restored, and normal operating status is confirmed
- [RC.RP-06](../subcategories/rc.rp-06.md) - The end of incident recovery is declared based on criteria, and incident-related documentation is completed

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
