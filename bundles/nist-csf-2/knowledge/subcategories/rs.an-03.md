---
type: framework_subcategory
title: RS.AN-03
description: Analysis is performed to establish what has taken place during an incident and the root cause of the
  incident
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
- rs-an-03
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
- name: Incident Analysis
  path: /bundles/nist-csf-2/knowledge/categories/rs.an.md
  relation: part_of
  description: This Subcategory is part of the RS.AN Category.
nist_id: RS.AN-03
implementation_example_count: 4
---

# Summary

Analysis is performed to establish what has taken place during an incident and the root cause of the incident

# Implementation Examples

- Determine the sequence of events that occurred during the incident and which assets and resources were involved in each event
- Attempt to determine what vulnerabilities, threats, and threat actors were directly or indirectly involved in the incident
- Analyze the incident to find the underlying, systemic root causes
- Check any cyber deception technology for additional information on attacker behavior

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
