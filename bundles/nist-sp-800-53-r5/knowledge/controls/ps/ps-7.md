---
type: control
title: PS-7 - External Personnel Security
description: SP 800-53 control PS-7.
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
- ps
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ps.md
  relation: part_of
  description: PS-7 - External Personnel Security is part of its parent SP 800-53 structure.
nist_id: PS-7
sort_id: ps-07
implementation_level: organization
parameter_ids:
- ps-07_odp.01
- ps-07_odp.02
reference_links:
- '#77faf0bc-c394-44ad-9154-bbac3b79c8ad'
- '#737513fa-6758-403f-831d-5ddab5e23cb3'
- '#at-2'
- '#at-3'
- '#ma-5'
- '#pe-3'
- '#ps-2'
- '#ps-3'
- '#ps-4'
- '#ps-5'
- '#ps-6'
- '#sa-5'
- '#sa-9'
- '#sa-21'
---

# Summary

SP 800-53 control PS-7.

# Statement

No statement text was present in the OSCAL record.

# Guidance

External provider refers to organizations other than the organization operating or acquiring the system. External providers include service bureaus, contractors, and other organizations that provide system development, information technology services, testing or assessment services, outsourced applications, and network/security management. Organizations explicitly include personnel security requirements in acquisition-related documents. External providers may have personnel working at organizational facilities with credentials, badges, or system privileges issued by organizations. Notifications of external personnel changes ensure the appropriate termination of privileges and credentials. Organizations define the transfers and terminations deemed reportable by security-related characteristics that include functions, roles, and the nature of credentials or privileges associated with transferred or terminated individuals.

# Parameters

- `ps-07_odp.01`
- `ps-07_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
