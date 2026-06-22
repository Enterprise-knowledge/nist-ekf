---
type: framework_category
title: RS.AN - Incident Analysis
description: Investigations are conducted to ensure effective response and support forensics and recovery activities
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
- rs
- rs-an
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
- name: RESPOND
  path: /bundles/nist-csf-2/knowledge/functions/rs.md
  relation: part_of
  description: This Category is part of the RS Function.
- name: RS.AN-03
  path: /bundles/nist-csf-2/knowledge/subcategories/rs.an-03.md
  relation: contains
  description: RS.AN contains Subcategory RS.AN-03.
- name: RS.AN-06
  path: /bundles/nist-csf-2/knowledge/subcategories/rs.an-06.md
  relation: contains
  description: RS.AN contains Subcategory RS.AN-06.
- name: RS.AN-07
  path: /bundles/nist-csf-2/knowledge/subcategories/rs.an-07.md
  relation: contains
  description: RS.AN contains Subcategory RS.AN-07.
- name: RS.AN-08
  path: /bundles/nist-csf-2/knowledge/subcategories/rs.an-08.md
  relation: contains
  description: RS.AN contains Subcategory RS.AN-08.
nist_id: RS.AN
---

# Summary

Investigations are conducted to ensure effective response and support forensics and recovery activities

# Structure

This Category is part of `RS` and contains 4 active Subcategories.

## Subcategories

- [RS.AN-03](../subcategories/rs.an-03.md) - Analysis is performed to establish what has taken place during an incident and the root cause of the incident
- [RS.AN-06](../subcategories/rs.an-06.md) - Actions performed during an investigation are recorded, and the records' integrity and provenance are preserved
- [RS.AN-07](../subcategories/rs.an-07.md) - Incident data and metadata are collected, and their integrity and provenance are preserved
- [RS.AN-08](../subcategories/rs.an-08.md) - An incident's magnitude is estimated and validated

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
