---
type: framework_subcategory
title: DE.CM-02
description: The physical environment is monitored to find potentially adverse events
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
- de-cm-02
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
- name: Continuous Monitoring
  path: /bundles/nist-csf-2/knowledge/categories/de.cm.md
  relation: part_of
  description: This Subcategory is part of the DE.CM Category.
nist_id: DE.CM-02
implementation_example_count: 4
---

# Summary

The physical environment is monitored to find potentially adverse events

# Implementation Examples

- Monitor logs from physical access control systems (e.g., badge readers) to find unusual access patterns (e.g., deviations from the norm) and failed access attempts
- Review and monitor physical access records (e.g., from visitor registration, sign-in sheets)
- Monitor physical access controls (e.g., locks, latches, hinge pins, alarms) for signs of tampering
- Monitor the physical environment using alarm systems, cameras, and security guards

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
