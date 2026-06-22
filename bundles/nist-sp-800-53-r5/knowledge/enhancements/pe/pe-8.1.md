---
type: control_enhancement
title: PE-8.1 - Automated Records Maintenance and Review
description: 'Maintain and review visitor access records using {{ insert: param, pe-8.1_prm_1 }}.'
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
- pe
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-8.md
  relation: part_of
  description: PE-8.1 - Automated Records Maintenance and Review is part of its parent SP 800-53 structure.
- name: PE-8 - Visitor Access Records
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-8.md
  relation: enhances
  description: PE-8.1 enhances base control PE-8.
nist_id: PE-8.1
sort_id: pe-08.01
implementation_level: organization
parameter_ids:
- pe-8.1_prm_1
- pe-08.01_odp.01
- pe-08.01_odp.02
reference_links:
- '#pe-8'
---

# Summary

Maintain and review visitor access records using {{ insert: param, pe-8.1_prm_1 }}.

# Statement

Maintain and review visitor access records using {{ insert: param, pe-8.1_prm_1 }}.

# Guidance

Visitor access records may be stored and maintained in a database management system that is accessible by organizational personnel. Automated access to such records facilitates record reviews on a regular basis to determine if access authorizations are current and still required to support organizational mission and business functions.

# Parameters

- `pe-8.1_prm_1`
- `pe-08.01_odp.01`
- `pe-08.01_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
