---
type: control_enhancement
title: IR-7.1 - Automation Support for Availability of Information and Support
description: 'Increase the availability of incident response information and support using {{ insert: param, ir-07.01_odp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-7.md
  relation: part_of
  description: IR-7.1 - Automation Support for Availability of Information and Support is part of its parent SP
    800-53 structure.
- name: IR-7 - Incident Response Assistance
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-7.md
  relation: enhances
  description: IR-7.1 enhances base control IR-7.
nist_id: IR-7.1
sort_id: ir-07.01
implementation_level: organization
parameter_ids:
- ir-07.01_odp
reference_links:
- '#ir-7'
---

# Summary

Increase the availability of incident response information and support using {{ insert: param, ir-07.01_odp }}.

# Statement

Increase the availability of incident response information and support using {{ insert: param, ir-07.01_odp }}.

# Guidance

Automated mechanisms can provide a push or pull capability for users to obtain incident response assistance. For example, individuals may have access to a website to query the assistance capability, or the assistance capability can proactively send incident response information to users (general distribution or targeted) as part of increasing understanding of current response capabilities and support.

# Parameters

- `ir-07.01_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
