---
type: framework_subcategory
title: RS.MA-03
description: Incidents are categorized and prioritized
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: cybersecurity-risk-management
system: nist-csf-2
tags:
- nist
- csf
- subcategory
- rs-ma-03
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
- name: Incident Management
  path: /bundles/nist-csf-2/knowledge/categories/rs.ma.md
  relation: part_of
  description: This Subcategory is part of the RS.MA Category.
nist_id: RS.MA-03
implementation_example_count: 3
---

# Summary

Incidents are categorized and prioritized

# Implementation Examples

- Further review and categorize incidents based on the type of incident (e.g., data breach, ransomware, DDoS, account compromise)
- Prioritize incidents based on their scope, likely impact, and time-critical nature
- Select incident response strategies for active incidents by balancing the need to quickly recover from an incident with the need to observe the attacker or conduct a more thorough investigation

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
