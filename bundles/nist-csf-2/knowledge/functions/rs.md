---
type: framework_function
title: RS - Respond
description: Actions regarding a detected cybersecurity incident are taken
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
- rs
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
- name: Incident Analysis
  path: /bundles/nist-csf-2/knowledge/categories/rs.an.md
  relation: contains
  description: RS contains the RS.AN Category.
- name: Incident Response Reporting and Communication
  path: /bundles/nist-csf-2/knowledge/categories/rs.co.md
  relation: contains
  description: RS contains the RS.CO Category.
- name: Incident Management
  path: /bundles/nist-csf-2/knowledge/categories/rs.ma.md
  relation: contains
  description: RS contains the RS.MA Category.
- name: Incident Mitigation
  path: /bundles/nist-csf-2/knowledge/categories/rs.mi.md
  relation: contains
  description: RS contains the RS.MI Category.
nist_id: RS
---

# Summary

Actions regarding a detected cybersecurity incident are taken

# Structure

This Function contains 4 Categories.

## Categories

- [RS.AN - Incident Analysis](../categories/rs.an.md) - Investigations are conducted to ensure effective response and support forensics and recovery activities
- [RS.CO - Incident Response Reporting and Communication](../categories/rs.co.md) - Response activities are coordinated with internal and external stakeholders as required by laws, regulations, or policies
- [RS.MA - Incident Management](../categories/rs.ma.md) - Responses to detected cybersecurity incidents are managed
- [RS.MI - Incident Mitigation](../categories/rs.mi.md) - Activities are performed to prevent expansion of an event and mitigate its effects

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
