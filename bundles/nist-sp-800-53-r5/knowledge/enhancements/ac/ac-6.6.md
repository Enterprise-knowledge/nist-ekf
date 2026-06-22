---
type: control_enhancement
title: AC-6.6 - Privileged Access by Non-organizational Users
description: Prohibit privileged access to the system by non-organizational users.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-6.md
  relation: part_of
  description: AC-6.6 - Privileged Access by Non-organizational Users is part of its parent SP 800-53 structure.
- name: AC-6 - Least Privilege
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-6.md
  relation: enhances
  description: AC-6.6 enhances base control AC-6.
nist_id: AC-6.6
sort_id: ac-06.06
implementation_level: organization
parameter_ids: []
reference_links:
- '#ac-6'
- '#ac-18'
- '#ac-19'
- '#ia-2'
- '#ia-8'
---

# Summary

Prohibit privileged access to the system by non-organizational users.

# Statement

Prohibit privileged access to the system by non-organizational users.

# Guidance

An organizational user is an employee or an individual considered by the organization to have the equivalent status of an employee. Organizational users include contractors, guest researchers, or individuals detailed from other organizations. A non-organizational user is a user who is not an organizational user. Policies and procedures for granting equivalent status of employees to individuals include a need-to-know, citizenship, and the relationship to the organization.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
