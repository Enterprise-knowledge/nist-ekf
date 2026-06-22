---
type: control
title: IR-8 - Incident Response Plan
description: SP 800-53 control IR-8.
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
- ir
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ir.md
  relation: part_of
  description: IR-8 - Incident Response Plan is part of its parent SP 800-53 structure.
- name: IR-8.1 - Breaches
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-8.1.md
  relation: has_enhancement
  description: IR-8 has enhancement IR-8.1.
nist_id: IR-8
sort_id: ir-08
implementation_level: organization
parameter_ids:
- ir-8_prm_5
- ir-08_odp.01
- ir-08_odp.02
- ir-08_odp.03
- ir-08_odp.04
- ir-08_odp.05
- ir-08_odp.06
- ir-08_odp.07
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#49b8aa2d-a88c-4bff-9f20-876ccb8f7dcb'
- '#5f4705ac-8d17-438c-b23a-ac7f12362ae4'
- '#ac-2'
- '#cp-2'
- '#cp-4'
- '#ir-4'
- '#ir-7'
- '#ir-9'
- '#pe-6'
- '#pl-2'
- '#sa-15'
- '#si-12'
- '#sr-8'
---

# Summary

SP 800-53 control IR-8.

# Statement

No statement text was present in the OSCAL record.

# Guidance

It is important that organizations develop and implement a coordinated approach to incident response. Organizational mission and business functions determine the structure of incident response capabilities. As part of the incident response capabilities, organizations consider the coordination and sharing of information with external organizations, including external service providers and other organizations involved in the supply chain. For incidents involving personally identifiable information (i.e., breaches), include a process to determine whether notice to oversight organizations or affected individuals is appropriate and provide that notice accordingly.

# Parameters

- `ir-8_prm_5`
- `ir-08_odp.01`
- `ir-08_odp.02`
- `ir-08_odp.03`
- `ir-08_odp.04`
- `ir-08_odp.05`
- `ir-08_odp.06`
- `ir-08_odp.07`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
