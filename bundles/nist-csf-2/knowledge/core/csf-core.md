---
type: framework_core
title: CSF Core
description: The CSF 2.0 Core organizes cybersecurity outcomes into Functions, Categories, and Subcategories.
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: cybersecurity-risk-management
system: nist-csf-2
tags:
- nist
- csf
- core
- cybersecurity-outcomes
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
- name: NIST CSWP 29
  path: /bundles/nist-csf-2/knowledge/publication.md
  relation: part_of
  description: The CSF Core is defined by the CSF 2.0 publication.
- name: GOVERN
  path: /bundles/nist-csf-2/knowledge/functions/gv.md
  relation: contains
  description: The Core contains the GOVERN Function.
- name: IDENTIFY
  path: /bundles/nist-csf-2/knowledge/functions/id.md
  relation: contains
  description: The Core contains the IDENTIFY Function.
- name: PROTECT
  path: /bundles/nist-csf-2/knowledge/functions/pr.md
  relation: contains
  description: The Core contains the PROTECT Function.
- name: DETECT
  path: /bundles/nist-csf-2/knowledge/functions/de.md
  relation: contains
  description: The Core contains the DETECT Function.
- name: RESPOND
  path: /bundles/nist-csf-2/knowledge/functions/rs.md
  relation: contains
  description: The Core contains the RESPOND Function.
- name: RECOVER
  path: /bundles/nist-csf-2/knowledge/functions/rc.md
  relation: contains
  description: The Core contains the RECOVER Function.
---

# Summary

The CSF Core provides a taxonomy of cybersecurity outcomes. This generated concept links to 6 Functions, 22 active Categories, and 106 active Subcategories.

# Scope

The Core is outcome-oriented and does not prescribe how outcomes must be achieved. Implementation Examples are embedded in Subcategory concepts when provided by the NIST CSF Reference Tool export.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
