---
type: framework_subcategory
title: DE.CM-06
description: External service provider activities and services are monitored to find potentially adverse events
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
- de-cm-06
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
nist_id: DE.CM-06
implementation_example_count: 2
---

# Summary

External service provider activities and services are monitored to find potentially adverse events

# Implementation Examples

- Monitor remote and onsite administration and maintenance activities that external providers perform on organizational systems
- Monitor activity from cloud-based services, internet service providers, and other service providers for deviations from expected behavior

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
