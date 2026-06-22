---
type: control
title: IR-6 - Incident Reporting
description: SP 800-53 control IR-6.
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
  description: IR-6 - Incident Reporting is part of its parent SP 800-53 structure.
- name: IR-6.1 - Automated Reporting
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-6.1.md
  relation: has_enhancement
  description: IR-6 has enhancement IR-6.1.
- name: IR-6.2 - Vulnerabilities Related to Incidents
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-6.2.md
  relation: has_enhancement
  description: IR-6 has enhancement IR-6.2.
- name: IR-6.3 - Supply Chain Coordination
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-6.3.md
  relation: has_enhancement
  description: IR-6 has enhancement IR-6.3.
nist_id: IR-6
sort_id: ir-06
implementation_level: organization
parameter_ids:
- ir-06_odp.01
- ir-06_odp.02
reference_links:
- '#4ff10ed3-d8fe-4246-99e3-443045e27482'
- '#0f963c17-ab5a-432a-a867-91eac550309b'
- '#40b78258-c892-480e-9af8-77ac36648301'
- '#49b8aa2d-a88c-4bff-9f20-876ccb8f7dcb'
- '#cm-6'
- '#cp-2'
- '#ir-4'
- '#ir-5'
- '#ir-8'
- '#ir-9'
---

# Summary

SP 800-53 control IR-6.

# Statement

No statement text was present in the OSCAL record.

# Guidance

The types of incidents reported, the content and timeliness of the reports, and the designated reporting authorities reflect applicable laws, executive orders, directives, regulations, policies, standards, and guidelines. Incident information can inform risk assessments, control effectiveness assessments, security requirements for acquisitions, and selection criteria for technology products.

# Parameters

- `ir-06_odp.01`
- `ir-06_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
