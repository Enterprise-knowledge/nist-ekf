---
type: framework_category
title: DE.CM - Continuous Monitoring
description: Assets are monitored to find anomalies, indicators of compromise, and other potentially adverse events
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
- de
- de-cm
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
- name: DETECT
  path: /bundles/nist-csf-2/knowledge/functions/de.md
  relation: part_of
  description: This Category is part of the DE Function.
- name: DE.CM-01
  path: /bundles/nist-csf-2/knowledge/subcategories/de.cm-01.md
  relation: contains
  description: DE.CM contains Subcategory DE.CM-01.
- name: DE.CM-02
  path: /bundles/nist-csf-2/knowledge/subcategories/de.cm-02.md
  relation: contains
  description: DE.CM contains Subcategory DE.CM-02.
- name: DE.CM-03
  path: /bundles/nist-csf-2/knowledge/subcategories/de.cm-03.md
  relation: contains
  description: DE.CM contains Subcategory DE.CM-03.
- name: DE.CM-06
  path: /bundles/nist-csf-2/knowledge/subcategories/de.cm-06.md
  relation: contains
  description: DE.CM contains Subcategory DE.CM-06.
- name: DE.CM-09
  path: /bundles/nist-csf-2/knowledge/subcategories/de.cm-09.md
  relation: contains
  description: DE.CM contains Subcategory DE.CM-09.
nist_id: DE.CM
---

# Summary

Assets are monitored to find anomalies, indicators of compromise, and other potentially adverse events

# Structure

This Category is part of `DE` and contains 5 active Subcategories.

## Subcategories

- [DE.CM-01](../subcategories/de.cm-01.md) - Networks and network services are monitored to find potentially adverse events
- [DE.CM-02](../subcategories/de.cm-02.md) - The physical environment is monitored to find potentially adverse events
- [DE.CM-03](../subcategories/de.cm-03.md) - Personnel activity and technology usage are monitored to find potentially adverse events
- [DE.CM-06](../subcategories/de.cm-06.md) - External service provider activities and services are monitored to find potentially adverse events
- [DE.CM-09](../subcategories/de.cm-09.md) - Computing hardware and software, runtime environments, and their data are monitored to find potentially adverse events

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
