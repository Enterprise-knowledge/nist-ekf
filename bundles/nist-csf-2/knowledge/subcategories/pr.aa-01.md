---
type: framework_subcategory
title: PR.AA-01
description: Identities and credentials for authorized users, services, and hardware are managed by the organization
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
- pr-aa-01
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
- name: Identity Management, Authentication, and Access Control
  path: /bundles/nist-csf-2/knowledge/categories/pr.aa.md
  relation: part_of
  description: This Subcategory is part of the PR.AA Category.
nist_id: PR.AA-01
implementation_example_count: 4
---

# Summary

Identities and credentials for authorized users, services, and hardware are managed by the organization

# Implementation Examples

- Initiate requests for new access or additional access for employees, contractors, and others, and track, review, and fulfill the requests, with permission from system or data owners when needed
- Issue, manage, and revoke cryptographic certificates and identity tokens, cryptographic keys (i.e., key management), and other credentials
- Select a unique identifier for each device from immutable hardware characteristics or an identifier securely provisioned to the device
- Physically label authorized hardware with an identifier for inventory and servicing purposes

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
