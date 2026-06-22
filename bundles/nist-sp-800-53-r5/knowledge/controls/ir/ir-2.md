---
type: control
title: IR-2 - Incident Response Training
description: SP 800-53 control IR-2.
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
  description: IR-2 - Incident Response Training is part of its parent SP 800-53 structure.
- name: IR-2.1 - Simulated Events
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-2.1.md
  relation: has_enhancement
  description: IR-2 has enhancement IR-2.1.
- name: IR-2.2 - Automated Training Environments
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-2.2.md
  relation: has_enhancement
  description: IR-2 has enhancement IR-2.2.
- name: IR-2.3 - Breach
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-2.3.md
  relation: has_enhancement
  description: IR-2 has enhancement IR-2.3.
nist_id: IR-2
sort_id: ir-02
implementation_level: organization
parameter_ids:
- ir-02_odp.01
- ir-02_odp.02
- ir-02_odp.03
- ir-02_odp.04
reference_links:
- '#5f4705ac-8d17-438c-b23a-ac7f12362ae4'
- '#511f6832-23ca-49a3-8c0f-ce493373cab8'
- '#at-2'
- '#at-3'
- '#at-4'
- '#cp-3'
- '#ir-3'
- '#ir-4'
- '#ir-8'
- '#ir-9'
---

# Summary

SP 800-53 control IR-2.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Incident response training is associated with the assigned roles and responsibilities of organizational personnel to ensure that the appropriate content and level of detail are included in such training. For example, users may only need to know who to call or how to recognize an incident; system administrators may require additional training on how to handle incidents; and incident responders may receive more specific training on forensics, data collection techniques, reporting, system recovery, and system restoration. Incident response training includes user training in identifying and reporting suspicious activities from external and internal sources. Incident response training for users may be provided as part of [AT-2](#at-2) or [AT-3](#at-3) . Events that may precipitate an update to incident response training content include, but are not limited to, incident response plan testing or response to an actual incident (lessons learned), assessment or audit findings, or changes in applicable laws, executive orders, directives, regulations, policies, standards, and guidelines.

# Parameters

- `ir-02_odp.01`
- `ir-02_odp.02`
- `ir-02_odp.03`
- `ir-02_odp.04`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
