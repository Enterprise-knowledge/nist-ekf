---
type: framework_category
title: DE.AE - Adverse Event Analysis
description: Anomalies, indicators of compromise, and other potentially adverse events are analyzed to characterize
  the events and detect cybersecurity incidents
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
- de-ae
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
- name: DE.AE-02
  path: /bundles/nist-csf-2/knowledge/subcategories/de.ae-02.md
  relation: contains
  description: DE.AE contains Subcategory DE.AE-02.
- name: DE.AE-03
  path: /bundles/nist-csf-2/knowledge/subcategories/de.ae-03.md
  relation: contains
  description: DE.AE contains Subcategory DE.AE-03.
- name: DE.AE-04
  path: /bundles/nist-csf-2/knowledge/subcategories/de.ae-04.md
  relation: contains
  description: DE.AE contains Subcategory DE.AE-04.
- name: DE.AE-06
  path: /bundles/nist-csf-2/knowledge/subcategories/de.ae-06.md
  relation: contains
  description: DE.AE contains Subcategory DE.AE-06.
- name: DE.AE-07
  path: /bundles/nist-csf-2/knowledge/subcategories/de.ae-07.md
  relation: contains
  description: DE.AE contains Subcategory DE.AE-07.
- name: DE.AE-08
  path: /bundles/nist-csf-2/knowledge/subcategories/de.ae-08.md
  relation: contains
  description: DE.AE contains Subcategory DE.AE-08.
nist_id: DE.AE
---

# Summary

Anomalies, indicators of compromise, and other potentially adverse events are analyzed to characterize the events and detect cybersecurity incidents

# Structure

This Category is part of `DE` and contains 6 active Subcategories.

## Subcategories

- [DE.AE-02](../subcategories/de.ae-02.md) - Potentially adverse events are analyzed to better understand associated activities
- [DE.AE-03](../subcategories/de.ae-03.md) - Information is correlated from multiple sources
- [DE.AE-04](../subcategories/de.ae-04.md) - The estimated impact and scope of adverse events are understood
- [DE.AE-06](../subcategories/de.ae-06.md) - Information on adverse events is provided to authorized staff and tools
- [DE.AE-07](../subcategories/de.ae-07.md) - Cyber threat intelligence and other contextual information are integrated into the analysis
- [DE.AE-08](../subcategories/de.ae-08.md) - Incidents are declared when adverse events meet the defined incident criteria

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
