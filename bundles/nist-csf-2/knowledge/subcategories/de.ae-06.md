---
type: framework_subcategory
title: DE.AE-06
description: Information on adverse events is provided to authorized staff and tools
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
- de-ae-06
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
- name: Adverse Event Analysis
  path: /bundles/nist-csf-2/knowledge/categories/de.ae.md
  relation: part_of
  description: This Subcategory is part of the DE.AE Category.
nist_id: DE.AE-06
implementation_example_count: 4
---

# Summary

Information on adverse events is provided to authorized staff and tools

# Implementation Examples

- Use cybersecurity software to generate alerts and provide them to the security operations center (SOC), incident responders, and incident response tools
- Incident responders and other authorized personnel can access log analysis findings at all times
- Automatically create and assign tickets in the organization's ticketing system when certain types of alerts occur
- Manually create and assign tickets in the organization's ticketing system when technical staff discover indicators of compromise

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
