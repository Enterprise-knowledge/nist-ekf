---
type: control_enhancement
title: MP-6.3 - Nondestructive Techniques
description: 'Apply nondestructive sanitization techniques to portable storage devices prior to connecting such
  devices to the system under the following circumstances: {{ insert: param, mp-06.03_odp }}.'
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
- mp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-6.md
  relation: part_of
  description: MP-6.3 - Nondestructive Techniques is part of its parent SP 800-53 structure.
- name: MP-6 - Media Sanitization
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/mp/mp-6.md
  relation: enhances
  description: MP-6.3 enhances base control MP-6.
nist_id: MP-6.3
sort_id: mp-06.03
implementation_level: organization
parameter_ids:
- mp-06.03_odp
reference_links:
- '#mp-6'
---

# Summary

Apply nondestructive sanitization techniques to portable storage devices prior to connecting such devices to the system under the following circumstances: {{ insert: param, mp-06.03_odp }}.

# Statement

Apply nondestructive sanitization techniques to portable storage devices prior to connecting such devices to the system under the following circumstances: {{ insert: param, mp-06.03_odp }}.

# Guidance

Portable storage devices include external or removable hard disk drives (e.g., solid state, magnetic), optical discs, magnetic or optical tapes, flash memory devices, flash memory cards, and other external or removable disks. Portable storage devices can be obtained from untrustworthy sources and contain malicious code that can be inserted into or transferred to organizational systems through USB ports or other entry portals. While scanning storage devices is recommended, sanitization provides additional assurance that such devices are free of malicious code. Organizations consider nondestructive sanitization of portable storage devices when the devices are purchased from manufacturers or vendors prior to initial use or when organizations cannot maintain a positive chain of custody for the devices.

# Parameters

- `mp-06.03_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
