---
type: framework_subcategory
title: PR.IR-01
description: Networks and environments are protected from unauthorized logical access and usage
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
- pr-ir-01
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
- name: Technology Infrastructure Resilience
  path: /bundles/nist-csf-2/knowledge/categories/pr.ir.md
  relation: part_of
  description: This Subcategory is part of the PR.IR Category.
nist_id: PR.IR-01
implementation_example_count: 4
---

# Summary

Networks and environments are protected from unauthorized logical access and usage

# Implementation Examples

- Logically segment organization networks and cloud-based platforms according to trust boundaries and platform types (e.g., IT, IoT, OT, mobile, guests), and permit required communications only between segments
- Logically segment organization networks from external networks, and permit only necessary communications to enter the organization's networks from the external networks
- Implement zero trust architectures to restrict network access to each resource to the minimum necessary
- Check the cyber health of endpoints before allowing them to access and use production resources

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
