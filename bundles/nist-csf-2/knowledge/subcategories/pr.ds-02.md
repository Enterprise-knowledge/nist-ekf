---
type: framework_subcategory
title: PR.DS-02
description: The confidentiality, integrity, and availability of data-in-transit are protected
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
- pr-ds-02
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
- name: Data Security
  path: /bundles/nist-csf-2/knowledge/categories/pr.ds.md
  relation: part_of
  description: This Subcategory is part of the PR.DS Category.
nist_id: PR.DS-02
implementation_example_count: 4
---

# Summary

The confidentiality, integrity, and availability of data-in-transit are protected

# Implementation Examples

- Use encryption, digital signatures, and cryptographic hashes to protect the confidentiality and integrity of network communications
- Automatically encrypt or block outbound emails and other communications that contain sensitive data, depending on the data classification
- Block access to personal email, file sharing, file storage services, and other personal communications applications and services from organizational systems and networks
- Prevent reuse of sensitive data from production environments (e.g., customer records) in development, testing, and other non-production environments

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
