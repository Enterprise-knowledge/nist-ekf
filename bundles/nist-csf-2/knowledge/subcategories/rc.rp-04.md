---
type: framework_subcategory
title: RC.RP-04
description: Critical mission functions and cybersecurity risk management are considered to establish post-incident
  operational norms
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
- rc-rp-04
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
- name: Incident Recovery Plan Execution
  path: /bundles/nist-csf-2/knowledge/categories/rc.rp.md
  relation: part_of
  description: This Subcategory is part of the RC.RP Category.
nist_id: RC.RP-04
implementation_example_count: 3
---

# Summary

Critical mission functions and cybersecurity risk management are considered to establish post-incident operational norms

# Implementation Examples

- Use business impact and system categorization records (including service delivery objectives) to validate that essential services are restored in the appropriate order
- Work with system owners to confirm the successful restoration of systems and the return to normal operations
- Monitor the performance of restored systems to verify the adequacy of the restoration

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
