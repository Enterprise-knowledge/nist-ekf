---
type: framework_subcategory
title: ID.AM-03
description: Representations of the organization's authorized network communication and internal and external network
  data flows are maintained
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
- id-am-03
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
- name: Asset Management
  path: /bundles/nist-csf-2/knowledge/categories/id.am.md
  relation: part_of
  description: This Subcategory is part of the ID.AM Category.
nist_id: ID.AM-03
implementation_example_count: 4
---

# Summary

Representations of the organization's authorized network communication and internal and external network data flows are maintained

# Implementation Examples

- Maintain baselines of communication and data flows within the organization's wired and wireless networks
- Maintain baselines of communication and data flows between the organization and third parties
- Maintain baselines of communication and data flows for the organization's infrastructure-as-a-service (IaaS) usage
- Maintain documentation of expected network ports, protocols, and services that are typically used among authorized systems

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
