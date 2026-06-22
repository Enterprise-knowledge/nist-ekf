---
type: control
title: PS-5 - Personnel Transfer
description: SP 800-53 control PS-5.
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
  description: PS-5 - Personnel Transfer is part of its parent SP 800-53 structure.
nist_id: PS-5
sort_id: ps-05
implementation_level: organization
parameter_ids:
- ps-05_odp.01
- ps-05_odp.02
- ps-05_odp.03
- ps-05_odp.04
reference_links:
- '#ac-2'
- '#ia-4'
- '#pe-2'
- '#pm-12'
- '#ps-4'
- '#ps-7'
---

# Summary

SP 800-53 control PS-5.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Personnel transfer applies when reassignments or transfers of individuals are permanent or of such extended duration as to make the actions warranted. Organizations define actions appropriate for the types of reassignments or transfers, whether permanent or extended. Actions that may be required for personnel transfers or reassignments to other positions within organizations include returning old and issuing new keys, identification cards, and building passes; closing system accounts and establishing new accounts; changing system access authorizations (i.e., privileges); and providing for access to official records to which individuals had access at previous work locations and in previous system accounts.

# Parameters

- `ps-05_odp.01`
- `ps-05_odp.02`
- `ps-05_odp.03`
- `ps-05_odp.04`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
