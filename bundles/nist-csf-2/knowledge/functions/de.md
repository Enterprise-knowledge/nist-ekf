---
type: framework_function
title: DE - Detect
description: Possible cybersecurity attacks and compromises are found and analyzed
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
- de
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
- name: Adverse Event Analysis
  path: /bundles/nist-csf-2/knowledge/categories/de.ae.md
  relation: contains
  description: DE contains the DE.AE Category.
- name: Continuous Monitoring
  path: /bundles/nist-csf-2/knowledge/categories/de.cm.md
  relation: contains
  description: DE contains the DE.CM Category.
nist_id: DE
---

# Summary

Possible cybersecurity attacks and compromises are found and analyzed

# Structure

This Function contains 2 Categories.

## Categories

- [DE.AE - Adverse Event Analysis](../categories/de.ae.md) - Anomalies, indicators of compromise, and other potentially adverse events are analyzed to characterize the events and detect cybersecurity incidents
- [DE.CM - Continuous Monitoring](../categories/de.cm.md) - Assets are monitored to find anomalies, indicators of compromise, and other potentially adverse events

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
