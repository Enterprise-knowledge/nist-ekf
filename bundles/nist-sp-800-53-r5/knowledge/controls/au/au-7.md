---
type: control
title: AU-7 - Audit Record Reduction and Report Generation
description: 'Provide and implement an audit record reduction and report generation capability that:'
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
  description: AU-7 - Audit Record Reduction and Report Generation is part of its parent SP 800-53 structure.
- name: AU-7.1 - Automatic Processing
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-7.1.md
  relation: has_enhancement
  description: AU-7 has enhancement AU-7.1.
- name: AU-7.2 - Automatic Sort and Search
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-7.2.md
  relation: has_enhancement
  description: AU-7 has enhancement AU-7.2.
nist_id: AU-7
sort_id: au-07
implementation_level: system
parameter_ids: []
reference_links:
- '#ac-2'
- '#au-2'
- '#au-3'
- '#au-4'
- '#au-5'
- '#au-6'
- '#au-12'
- '#au-16'
- '#cm-5'
- '#ia-5'
- '#ir-4'
- '#pm-12'
- '#si-4'
---

# Summary

Provide and implement an audit record reduction and report generation capability that:

# Statement

Provide and implement an audit record reduction and report generation capability that:

# Guidance

Audit record reduction is a process that manipulates collected audit log information and organizes it into a summary format that is more meaningful to analysts. Audit record reduction and report generation capabilities do not always emanate from the same system or from the same organizational entities that conduct audit logging activities. The audit record reduction capability includes modern data mining techniques with advanced data filters to identify anomalous behavior in audit records. The report generation capability provided by the system can generate customizable reports. Time ordering of audit records can be an issue if the granularity of the timestamp in the record is insufficient.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
