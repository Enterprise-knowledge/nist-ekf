---
type: control_enhancement
title: PE-6.1 - Intrusion Alarms and Surveillance Equipment
description: Monitor physical access to the facility where the system resides using physical intrusion alarms and
  surveillance equipment.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-6.md
  relation: part_of
  description: PE-6.1 - Intrusion Alarms and Surveillance Equipment is part of its parent SP 800-53 structure.
- name: PE-6 - Monitoring Physical Access
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pe/pe-6.md
  relation: enhances
  description: PE-6.1 enhances base control PE-6.
nist_id: PE-6.1
sort_id: pe-06.01
implementation_level: organization
parameter_ids: []
reference_links:
- '#pe-6'
---

# Summary

Monitor physical access to the facility where the system resides using physical intrusion alarms and surveillance equipment.

# Statement

Monitor physical access to the facility where the system resides using physical intrusion alarms and surveillance equipment.

# Guidance

Physical intrusion alarms can be employed to alert security personnel when unauthorized access to the facility is attempted. Alarm systems work in conjunction with physical barriers, physical access control systems, and security guards by triggering a response when these other forms of security have been compromised or breached. Physical intrusion alarms can include different types of sensor devices, such as motion sensors, contact sensors, and broken glass sensors. Surveillance equipment includes video cameras installed at strategic locations throughout the facility.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
