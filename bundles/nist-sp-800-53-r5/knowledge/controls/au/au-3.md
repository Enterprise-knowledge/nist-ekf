---
type: control
title: AU-3 - Content of Audit Records
description: 'Ensure that audit records contain information that establishes the following:'
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
  description: AU-3 - Content of Audit Records is part of its parent SP 800-53 structure.
- name: AU-3.1 - Additional Audit Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-3.1.md
  relation: has_enhancement
  description: AU-3 has enhancement AU-3.1.
- name: AU-3.2 - Centralized Management of Planned Audit Record Content
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-3.2.md
  relation: has_enhancement
  description: AU-3 has enhancement AU-3.2.
- name: AU-3.3 - Limit Personally Identifiable Information Elements
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-3.3.md
  relation: has_enhancement
  description: AU-3 has enhancement AU-3.3.
nist_id: AU-3
sort_id: au-03
implementation_level: system
parameter_ids: []
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#98d415ca-7281-4064-9931-0c366637e324'
- '#au-2'
- '#au-8'
- '#au-12'
- '#au-14'
- '#ma-4'
- '#pl-9'
- '#sa-8'
- '#si-7'
- '#si-11'
---

# Summary

Ensure that audit records contain information that establishes the following:

# Statement

Ensure that audit records contain information that establishes the following:

# Guidance

Audit record content that may be necessary to support the auditing function includes event descriptions (item a), time stamps (item b), source and destination addresses (item c), user or process identifiers (items d and f), success or fail indications (item e), and filenames involved (items a, c, e, and f) . Event outcomes include indicators of event success or failure and event-specific results, such as the system security and privacy posture after the event occurred. Organizations consider how audit records can reveal information about individuals that may give rise to privacy risks and how best to mitigate such risks. For example, there is the potential to reveal personally identifiable information in the audit trail, especially if the trail records inputs or is based on patterns or time of usage.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
