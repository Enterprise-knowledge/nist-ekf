---
type: framework_subcategory
title: PR.AA-05
description: Access permissions, entitlements, and authorizations are defined in a policy, managed, enforced, and
  reviewed, and incorporate the principles of least privilege and separation of duties
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
- pr-aa-05
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
nist_id: PR.AA-05
implementation_example_count: 4
---

# Summary

Access permissions, entitlements, and authorizations are defined in a policy, managed, enforced, and reviewed, and incorporate the principles of least privilege and separation of duties

# Implementation Examples

- Review logical and physical access privileges periodically and whenever someone changes roles or leaves the organization, and promptly rescind privileges that are no longer needed
- Take attributes of the requester and the requested resource into account for authorization decisions (e.g., geolocation, day/time, requester endpoint's cyber health)
- Restrict access and privileges to the minimum necessary (e.g., zero trust architecture)
- Periodically review the privileges associated with critical business functions to confirm proper separation of duties

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
