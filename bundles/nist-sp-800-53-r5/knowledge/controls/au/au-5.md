---
type: control
title: AU-5 - Response to Audit Logging Process Failures
description: SP 800-53 control AU-5.
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control
- au
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/au.md
  relation: part_of
  description: AU-5 - Response to Audit Logging Process Failures is part of its parent SP 800-53 structure.
- name: AU-5.1 - Storage Capacity Warning
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-5.1.md
  relation: has_enhancement
  description: AU-5 has enhancement AU-5.1.
- name: AU-5.2 - Real-time Alerts
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-5.2.md
  relation: has_enhancement
  description: AU-5 has enhancement AU-5.2.
- name: AU-5.3 - Configurable Traffic Volume Thresholds
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-5.3.md
  relation: has_enhancement
  description: AU-5 has enhancement AU-5.3.
- name: AU-5.4 - Shutdown on Failure
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-5.4.md
  relation: has_enhancement
  description: AU-5 has enhancement AU-5.4.
- name: AU-5.5 - Alternate Audit Logging Capability
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-5.5.md
  relation: has_enhancement
  description: AU-5 has enhancement AU-5.5.
nist_id: AU-5
sort_id: au-05
implementation_level: system
parameter_ids:
- au-05_odp.01
- au-05_odp.02
- au-05_odp.03
reference_links:
- '#au-2'
- '#au-4'
- '#au-7'
- '#au-9'
- '#au-11'
- '#au-12'
- '#au-14'
- '#si-4'
- '#si-12'
---

# Summary

SP 800-53 control AU-5.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Audit logging process failures include software and hardware errors, failures in audit log capturing mechanisms, and reaching or exceeding audit log storage capacity. Organization-defined actions include overwriting oldest audit records, shutting down the system, and stopping the generation of audit records. Organizations may choose to define additional actions for audit logging process failures based on the type of failure, the location of the failure, the severity of the failure, or a combination of such factors. When the audit logging process failure is related to storage, the response is carried out for the audit log storage repository (i.e., the distinct system component where the audit logs are stored), the system on which the audit logs reside, the total audit log storage capacity of the organization (i.e., all audit log storage repositories combined), or all three. Organizations may decide to take no additional actions after alerting designated roles or personnel.

# Parameters

- `au-05_odp.01`
- `au-05_odp.02`
- `au-05_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
