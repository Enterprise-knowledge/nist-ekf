---
type: framework_function
title: PR - Protect
description: Safeguards to manage the organization's cybersecurity risks are used
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: cybersecurity-risk-management
system: nist-csf-2
tags:
- nist
- csf
- function
- pr
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
- name: CSF Core
  path: /bundles/nist-csf-2/knowledge/core/csf-core.md
  relation: part_of
  description: This Function is part of the CSF Core.
- name: Identity Management, Authentication, and Access Control
  path: /bundles/nist-csf-2/knowledge/categories/pr.aa.md
  relation: contains
  description: PR contains the PR.AA Category.
- name: Awareness and Training
  path: /bundles/nist-csf-2/knowledge/categories/pr.at.md
  relation: contains
  description: PR contains the PR.AT Category.
- name: Data Security
  path: /bundles/nist-csf-2/knowledge/categories/pr.ds.md
  relation: contains
  description: PR contains the PR.DS Category.
- name: Technology Infrastructure Resilience
  path: /bundles/nist-csf-2/knowledge/categories/pr.ir.md
  relation: contains
  description: PR contains the PR.IR Category.
- name: Platform Security
  path: /bundles/nist-csf-2/knowledge/categories/pr.ps.md
  relation: contains
  description: PR contains the PR.PS Category.
nist_id: PR
---

# Summary

Safeguards to manage the organization's cybersecurity risks are used

# Structure

This Function contains 5 Categories.

## Categories

- [PR.AA - Identity Management, Authentication, and Access Control](../categories/pr.aa.md) - Access to physical and logical assets is limited to authorized users, services, and hardware and  managed commensurate with the assessed risk of unauthorized access
- [PR.AT - Awareness and Training](../categories/pr.at.md) - The organization's personnel are provided with cybersecurity awareness and training so that they can perform their cybersecurity-related tasks
- [PR.DS - Data Security](../categories/pr.ds.md) - Data are managed consistent with the organization's risk strategy to protect the confidentiality, integrity, and availability of information
- [PR.IR - Technology Infrastructure Resilience](../categories/pr.ir.md) - Security architectures are managed with the organization's risk strategy to protect asset confidentiality, integrity, and availability, and organizational resilience
- [PR.PS - Platform Security](../categories/pr.ps.md) - The hardware, software (e.g., firmware, operating systems, applications), and services of physical and virtual platforms are managed consistent with the organization's risk strategy to protect their confidentiality, integrity, and availability

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
