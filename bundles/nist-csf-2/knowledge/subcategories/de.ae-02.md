---
type: framework_subcategory
title: DE.AE-02
description: Potentially adverse events are analyzed to better understand associated activities
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
- de-ae-02
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
nist_id: DE.AE-02
implementation_example_count: 4
---

# Summary

Potentially adverse events are analyzed to better understand associated activities

# Implementation Examples

- Use security information and event management (SIEM) or other tools to continuously monitor log events for known malicious and suspicious activity
- Utilize up-to-date cyber threat intelligence in log analysis tools to improve detection accuracy and characterize threat actors, their methods, and indicators of compromise
- Regularly conduct manual reviews of log events for technologies that cannot be sufficiently monitored through automation
- Use log analysis tools to generate reports on their findings

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
