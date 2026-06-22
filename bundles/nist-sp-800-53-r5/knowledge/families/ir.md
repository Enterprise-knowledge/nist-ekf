---
type: control_family
title: IR - Incident Response
description: SP 800-53 control family for Incident Response.
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control-family
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
- name: The Controls
  path: /bundles/nist-sp-800-53-r5/knowledge/sections/controls.md
  relation: part_of
  description: This family is part of the controls section.
- name: IR-1 - Policy and Procedures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-1.md
  relation: contains
  description: The family contains control IR-1.
- name: IR-2 - Incident Response Training
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-2.md
  relation: contains
  description: The family contains control IR-2.
- name: IR-3 - Incident Response Testing
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-3.md
  relation: contains
  description: The family contains control IR-3.
- name: IR-4 - Incident Handling
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-4.md
  relation: contains
  description: The family contains control IR-4.
- name: IR-5 - Incident Monitoring
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-5.md
  relation: contains
  description: The family contains control IR-5.
- name: IR-6 - Incident Reporting
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-6.md
  relation: contains
  description: The family contains control IR-6.
- name: IR-7 - Incident Response Assistance
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-7.md
  relation: contains
  description: The family contains control IR-7.
- name: IR-8 - Incident Response Plan
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-8.md
  relation: contains
  description: The family contains control IR-8.
- name: IR-9 - Information Spillage Response
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-9.md
  relation: contains
  description: The family contains control IR-9.
- name: IR-10 - Integrated Information Security Analysis Team
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-10.md
  relation: contains
  description: The family contains control IR-10.
nist_id: IR
base_control_count: 10
control_enhancement_count: 32
---

# Summary

The Incident Response family contains 10 base controls and 32 control enhancements in the NIST OSCAL catalog.

# Controls

- [IR-1 - Policy and Procedures](../controls/ir/ir-1.md) - SP 800-53 control IR-1.
- [IR-2 - Incident Response Training](../controls/ir/ir-2.md) - SP 800-53 control IR-2.
- [IR-3 - Incident Response Testing](../controls/ir/ir-3.md) - Test the effectiveness of the incident response capability for the system {{ insert: param, ir-03_odp.01 }} using the following tests: {{ insert: param, ir-03_odp.02 }}.
- [IR-4 - Incident Handling](../controls/ir/ir-4.md) - SP 800-53 control IR-4.
- [IR-5 - Incident Monitoring](../controls/ir/ir-5.md) - Track and document incidents.
- [IR-6 - Incident Reporting](../controls/ir/ir-6.md) - SP 800-53 control IR-6.
- [IR-7 - Incident Response Assistance](../controls/ir/ir-7.md) - Provide an incident response support resource, integral to the organizational incident response capability, that offers advice and assistance to users of the system for the handling and reporting of incidents.
- [IR-8 - Incident Response Plan](../controls/ir/ir-8.md) - SP 800-53 control IR-8.
- [IR-9 - Information Spillage Response](../controls/ir/ir-9.md) - Respond to information spills by:
- [IR-10 - Integrated Information Security Analysis Team](../controls/ir/ir-10.md) - SP 800-53 control IR-10.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
