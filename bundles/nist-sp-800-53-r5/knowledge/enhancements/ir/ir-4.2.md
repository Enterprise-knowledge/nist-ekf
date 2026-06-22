---
type: control_enhancement
title: IR-4.2 - Dynamic Reconfiguration
description: 'Include the following types of dynamic reconfiguration for {{ insert: param, ir-04.02_odp.02 }} as
  part of the incident response capability: {{ insert: param, ir-04.02_odp.01 }}.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-4.md
  relation: part_of
  description: IR-4.2 - Dynamic Reconfiguration is part of its parent SP 800-53 structure.
- name: IR-4 - Incident Handling
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-4.md
  relation: enhances
  description: IR-4.2 enhances base control IR-4.
nist_id: IR-4.2
sort_id: ir-04.02
implementation_level: organization
parameter_ids:
- ir-04.02_odp.01
- ir-04.02_odp.02
reference_links:
- '#ir-4'
- '#ac-2'
- '#ac-4'
- '#cm-2'
---

# Summary

Include the following types of dynamic reconfiguration for {{ insert: param, ir-04.02_odp.02 }} as part of the incident response capability: {{ insert: param, ir-04.02_odp.01 }}.

# Statement

Include the following types of dynamic reconfiguration for {{ insert: param, ir-04.02_odp.02 }} as part of the incident response capability: {{ insert: param, ir-04.02_odp.01 }}.

# Guidance

Dynamic reconfiguration includes changes to router rules, access control lists, intrusion detection or prevention system parameters, and filter rules for guards or firewalls. Organizations may perform dynamic reconfiguration of systems to stop attacks, misdirect attackers, and isolate components of systems, thus limiting the extent of the damage from breaches or compromises. Organizations include specific time frames for achieving the reconfiguration of systems in the definition of the reconfiguration capability, considering the potential need for rapid response to effectively address cyber threats.

# Parameters

- `ir-04.02_odp.01`
- `ir-04.02_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
