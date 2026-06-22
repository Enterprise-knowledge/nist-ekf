---
type: framework_subcategory
title: DE.CM-09
description: Computing hardware and software, runtime environments, and their data are monitored to find potentially
  adverse events
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
- de-cm-09
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
nist_id: DE.CM-09
implementation_example_count: 5
---

# Summary

Computing hardware and software, runtime environments, and their data are monitored to find potentially adverse events

# Implementation Examples

- Monitor email, web, file sharing, collaboration services, and other common attack vectors to detect malware, phishing, data leaks and exfiltration, and other adverse events
- Monitor authentication attempts to identify attacks against credentials and unauthorized credential reuse
- Monitor software configurations for deviations from security baselines
- Monitor hardware and software for signs of tampering
- Use technologies with a presence on endpoints to detect cyber health issues (e.g., missing patches, malware infections, unauthorized software), and redirect the endpoints to a remediation environment before access is authorized

# Source Notes

The Subcategory statement is generated from the CSF 2.0 Reference Tool export and cross-checked against the CSF 2.0 PDF appendix structure.

# Citations

[1] [NIST CSF 2.0 PDF](/source/NIST.CSWP.29.pdf)
[2] [CSF Reference Tool export](/artifacts/data/csf-2.0-export.xlsx)
