---
type: control_enhancement
title: AC-3.10 - Audited Override of Access Control Mechanisms
description: 'Employ an audited override of automated access control mechanisms under {{ insert: param, ac-03.10_odp.01
  }} by {{ insert: param, ac-03.10_odp.02 }}.'
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
- ac
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-3.md
  relation: part_of
  description: AC-3.10 - Audited Override of Access Control Mechanisms is part of its parent SP 800-53 structure.
- name: AC-3 - Access Enforcement
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-3.md
  relation: enhances
  description: AC-3.10 enhances base control AC-3.
nist_id: AC-3.10
sort_id: ac-03.10
implementation_level: organization
parameter_ids:
- ac-03.10_odp.01
- ac-03.10_odp.02
reference_links:
- '#ac-3'
- '#au-2'
- '#au-6'
- '#au-10'
- '#au-12'
- '#au-14'
---

# Summary

Employ an audited override of automated access control mechanisms under {{ insert: param, ac-03.10_odp.01 }} by {{ insert: param, ac-03.10_odp.02 }}.

# Statement

Employ an audited override of automated access control mechanisms under {{ insert: param, ac-03.10_odp.01 }} by {{ insert: param, ac-03.10_odp.02 }}.

# Guidance

In certain situations, such as when there is a threat to human life or an event that threatens the organization’s ability to carry out critical missions or business functions, an override capability for access control mechanisms may be needed. Override conditions are defined by organizations and used only in those limited circumstances. Audit events are defined in [AU-2](#au-2) . Audit records are generated in [AU-12](#au-12).

# Parameters

- `ac-03.10_odp.01`
- `ac-03.10_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
