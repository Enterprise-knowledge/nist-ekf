---
type: framework_category
title: RS.MA - Incident Management
description: Responses to detected cybersecurity incidents are managed
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
- rs-ma
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
- name: RS.MA-01
  path: /bundles/nist-csf-2/knowledge/subcategories/rs.ma-01.md
  relation: contains
  description: RS.MA contains Subcategory RS.MA-01.
- name: RS.MA-02
  path: /bundles/nist-csf-2/knowledge/subcategories/rs.ma-02.md
  relation: contains
  description: RS.MA contains Subcategory RS.MA-02.
- name: RS.MA-03
  path: /bundles/nist-csf-2/knowledge/subcategories/rs.ma-03.md
  relation: contains
  description: RS.MA contains Subcategory RS.MA-03.
- name: RS.MA-04
  path: /bundles/nist-csf-2/knowledge/subcategories/rs.ma-04.md
  relation: contains
  description: RS.MA contains Subcategory RS.MA-04.
- name: RS.MA-05
  path: /bundles/nist-csf-2/knowledge/subcategories/rs.ma-05.md
  relation: contains
  description: RS.MA contains Subcategory RS.MA-05.
nist_id: RS.MA
---

# Summary

Responses to detected cybersecurity incidents are managed

# Structure

This Category is part of `RS` and contains 5 active Subcategories.

## Subcategories

- [RS.MA-01](../subcategories/rs.ma-01.md) - The incident response plan is executed in coordination with relevant third parties once an incident is declared
- [RS.MA-02](../subcategories/rs.ma-02.md) - Incident reports are triaged and validated
- [RS.MA-03](../subcategories/rs.ma-03.md) - Incidents are categorized and prioritized
- [RS.MA-04](../subcategories/rs.ma-04.md) - Incidents are escalated or elevated as needed
- [RS.MA-05](../subcategories/rs.ma-05.md) - The criteria for initiating incident recovery are applied

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
