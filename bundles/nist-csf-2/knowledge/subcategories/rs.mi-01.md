---
type: framework_subcategory
title: RS.MI-01
description: Incidents are contained
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
- rs-mi-01
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
- name: Incident Mitigation
  path: /bundles/nist-csf-2/knowledge/categories/rs.mi.md
  relation: part_of
  description: This Subcategory is part of the RS.MI Category.
nist_id: RS.MI-01
implementation_example_count: 4
---

# Summary

Incidents are contained

# Implementation Examples

- Cybersecurity technologies (e.g., antivirus software) and cybersecurity features of other technologies (e.g., operating systems, network infrastructure devices) automatically perform containment actions
- Allow incident responders to manually select and perform containment actions
- Allow a third party (e.g., internet service provider, managed security service provider) to perform containment actions on behalf of the organization
- Automatically transfer compromised endpoints to a remediation virtual local area network (VLAN)

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
