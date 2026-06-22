---
type: framework_category
title: RS.MI - Incident Mitigation
description: Activities are performed to prevent expansion of an event and mitigate its effects
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
- rs-mi
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
- name: RS.MI-01
  path: /bundles/nist-csf-2/knowledge/subcategories/rs.mi-01.md
  relation: contains
  description: RS.MI contains Subcategory RS.MI-01.
- name: RS.MI-02
  path: /bundles/nist-csf-2/knowledge/subcategories/rs.mi-02.md
  relation: contains
  description: RS.MI contains Subcategory RS.MI-02.
nist_id: RS.MI
---

# Summary

Activities are performed to prevent expansion of an event and mitigate its effects

# Structure

This Category is part of `RS` and contains 2 active Subcategories.

## Subcategories

- [RS.MI-01](../subcategories/rs.mi-01.md) - Incidents are contained
- [RS.MI-02](../subcategories/rs.mi-02.md) - Incidents are eradicated

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
