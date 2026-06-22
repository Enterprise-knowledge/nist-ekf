---
type: control_enhancement
title: CP-8.3 - Separation of Primary and Alternate Providers
description: Obtain alternate telecommunications services from providers that are separated from primary service
  providers to reduce susceptibility to the same threats.
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
- cp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-8.md
  relation: part_of
  description: CP-8.3 - Separation of Primary and Alternate Providers is part of its parent SP 800-53 structure.
- name: CP-8 - Telecommunications Services
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-8.md
  relation: enhances
  description: CP-8.3 enhances base control CP-8.
nist_id: CP-8.3
sort_id: cp-08.03
implementation_level: organization
parameter_ids: []
reference_links:
- '#cp-8'
---

# Summary

Obtain alternate telecommunications services from providers that are separated from primary service providers to reduce susceptibility to the same threats.

# Statement

Obtain alternate telecommunications services from providers that are separated from primary service providers to reduce susceptibility to the same threats.

# Guidance

Threats that affect telecommunications services are defined in organizational assessments of risk and include natural disasters, structural failures, cyber or physical attacks, and errors of omission or commission. Organizations can reduce common susceptibilities by minimizing shared infrastructure among telecommunications service providers and achieving sufficient geographic separation between services. Organizations may consider using a single service provider in situations where the service provider can provide alternate telecommunications services that meet the separation needs addressed in the risk assessment.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
