---
type: control_enhancement
title: SA-4.3 - Development Methods, Techniques, and Practices
description: 'Require the developer of the system, system component, or system service to demonstrate the use of
  a system development life cycle process that includes:'
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control-enhancement
- sa
confidence: high
review:
  status: agent-generated
  reviewed_by: EKF generation workflow
  reviewed_at: '2026-06-22T00:00:00Z'
sources:
- name: NIST SP 800-53 Rev. 5 PDF
  path: /source/NIST.SP.800-53r5.pdf
  kind: pdf
  description: Local source PDF for SP 800-53 Rev. 5.
- name: NIST OSCAL SP 800-53 catalog
  path: /artifacts/data/NIST_SP-800-53_rev5_catalog.json
  kind: oscal
  description: Official NIST OSCAL catalog used as structured supplemental data for controls and enhancements.
related:
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-4.md
  relation: part_of
  description: SA-4.3 - Development Methods, Techniques, and Practices is part of its parent SP 800-53 structure.
- name: SA-4 - Acquisition Process
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-4.md
  relation: enhances
  description: SA-4.3 enhances base control SA-4.
nist_id: SA-4.3
sort_id: sa-04.03
implementation_level: organization
parameter_ids:
- sa-04.03_odp.01
- sa-04.03_odp.02
- sa-04.03_odp.03
- sa-04.03_odp.04
- sa-04.03_odp.05
- sa-04.03_odp.06
- sa-04.03_odp.07
- sa-04.03_odp.08
reference_links:
- '#sa-4'
---

# Summary

Require the developer of the system, system component, or system service to demonstrate the use of a system development life cycle process that includes:

# Statement

Require the developer of the system, system component, or system service to demonstrate the use of a system development life cycle process that includes:

# Guidance

Following a system development life cycle that includes state-of-the-practice software development methods, systems engineering methods, systems security and privacy engineering methods, and quality control processes helps to reduce the number and severity of latent errors within systems, system components, and system services. Reducing the number and severity of such errors reduces the number of vulnerabilities in those systems, components, and services. Transparency in the methods and techniques that developers select and implement for systems engineering, systems security and privacy engineering, software development, component and system assessments, and quality control processes provides an increased level of assurance in the trustworthiness of the system, system component, or system service being acquired.

# Parameters

- `sa-04.03_odp.01`
- `sa-04.03_odp.02`
- `sa-04.03_odp.03`
- `sa-04.03_odp.04`
- `sa-04.03_odp.05`
- `sa-04.03_odp.06`
- `sa-04.03_odp.07`
- `sa-04.03_odp.08`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
