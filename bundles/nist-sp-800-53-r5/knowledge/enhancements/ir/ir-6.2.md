---
type: control_enhancement
title: IR-6.2 - Vulnerabilities Related to Incidents
description: 'Report system vulnerabilities associated with reported incidents to {{ insert: param, ir-06.02_odp
  }}.'
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-6.md
  relation: part_of
  description: IR-6.2 - Vulnerabilities Related to Incidents is part of its parent SP 800-53 structure.
- name: IR-6 - Incident Reporting
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-6.md
  relation: enhances
  description: IR-6.2 enhances base control IR-6.
nist_id: IR-6.2
sort_id: ir-06.02
implementation_level: organization
parameter_ids:
- ir-06.02_odp
reference_links:
- '#ir-6'
---

# Summary

Report system vulnerabilities associated with reported incidents to {{ insert: param, ir-06.02_odp }}.

# Statement

Report system vulnerabilities associated with reported incidents to {{ insert: param, ir-06.02_odp }}.

# Guidance

Reported incidents that uncover system vulnerabilities are analyzed by organizational personnel including system owners, mission and business owners, senior agency information security officers, senior agency officials for privacy, authorizing officials, and the risk executive (function). The analysis can serve to prioritize and initiate mitigation actions to address the discovered system vulnerability.

# Parameters

- `ir-06.02_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
