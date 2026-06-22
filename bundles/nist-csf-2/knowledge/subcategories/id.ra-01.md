---
type: framework_subcategory
title: ID.RA-01
description: Vulnerabilities in assets are identified, validated, and recorded
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
- id-ra-01
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
- name: Risk Assessment
  path: /bundles/nist-csf-2/knowledge/categories/id.ra.md
  relation: part_of
  description: This Subcategory is part of the ID.RA Category.
nist_id: ID.RA-01
implementation_example_count: 6
---

# Summary

Vulnerabilities in assets are identified, validated, and recorded

# Implementation Examples

- Use vulnerability management technologies to identify unpatched and misconfigured software
- Assess network and system architectures for design and implementation weaknesses that affect cybersecurity
- Review, analyze, or test organization-developed software to identify design, coding, and default configuration vulnerabilities
- Assess facilities that house critical computing assets for physical vulnerabilities and resilience issues
- Monitor sources of cyber threat intelligence for information on new vulnerabilities in products and services
- Review processes and procedures for weaknesses that could be exploited to affect cybersecurity

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
