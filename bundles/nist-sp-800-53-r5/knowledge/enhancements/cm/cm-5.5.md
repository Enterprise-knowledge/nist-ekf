---
type: control_enhancement
title: CM-5.5 - Privilege Limitation for Production and Operation
description: SP 800-53 control CM-5.5.
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
- cm
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-5.md
  relation: part_of
  description: CM-5.5 - Privilege Limitation for Production and Operation is part of its parent SP 800-53 structure.
- name: CM-5 - Access Restrictions for Change
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-5.md
  relation: enhances
  description: CM-5.5 enhances base control CM-5.
nist_id: CM-5.5
sort_id: cm-05.05
implementation_level: organization
parameter_ids:
- cm-5.5_prm_1
- cm-05.05_odp.01
- cm-05.05_odp.02
reference_links:
- '#cm-5'
- '#ac-2'
---

# Summary

SP 800-53 control CM-5.5.

# Statement

No statement text was present in the OSCAL record.

# Guidance

In many organizations, systems support multiple mission and business functions. Limiting privileges to change system components with respect to operational systems is necessary because changes to a system component may have far-reaching effects on mission and business processes supported by the system. The relationships between systems and mission/business processes are, in some cases, unknown to developers. System-related information includes operational procedures.

# Parameters

- `cm-5.5_prm_1`
- `cm-05.05_odp.01`
- `cm-05.05_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
