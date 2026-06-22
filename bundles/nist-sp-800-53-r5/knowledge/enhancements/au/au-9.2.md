---
type: control_enhancement
title: AU-9.2 - Store on Separate Physical Systems or Components
description: 'Store audit records {{ insert: param, au-09.02_odp }} in a repository that is part of a physically
  different system or system component than the system or component being audited.'
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-9.md
  relation: part_of
  description: AU-9.2 - Store on Separate Physical Systems or Components is part of its parent SP 800-53 structure.
- name: AU-9 - Protection of Audit Information
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-9.md
  relation: enhances
  description: AU-9.2 enhances base control AU-9.
nist_id: AU-9.2
sort_id: au-09.02
implementation_level: system
parameter_ids:
- au-09.02_odp
reference_links:
- '#au-9'
- '#au-4'
- '#au-5'
---

# Summary

Store audit records {{ insert: param, au-09.02_odp }} in a repository that is part of a physically different system or system component than the system or component being audited.

# Statement

Store audit records {{ insert: param, au-09.02_odp }} in a repository that is part of a physically different system or system component than the system or component being audited.

# Guidance

Storing audit records in a repository separate from the audited system or system component helps to ensure that a compromise of the system being audited does not also result in a compromise of the audit records. Storing audit records on separate physical systems or components also preserves the confidentiality and integrity of audit records and facilitates the management of audit records as an organization-wide activity. Storing audit records on separate systems or components applies to initial generation as well as backup or long-term storage of audit records.

# Parameters

- `au-09.02_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
