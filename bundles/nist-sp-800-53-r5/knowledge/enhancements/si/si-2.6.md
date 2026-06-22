---
type: control_enhancement
title: SI-2.6 - Removal of Previous Versions of Software and Firmware
description: 'Remove previous versions of {{ insert: param, si-02.06_odp }} after updated versions have been installed.'
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
- si
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-2.md
  relation: part_of
  description: SI-2.6 - Removal of Previous Versions of Software and Firmware is part of its parent SP 800-53 structure.
- name: SI-2 - Flaw Remediation
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-2.md
  relation: enhances
  description: SI-2.6 enhances base control SI-2.
nist_id: SI-2.6
sort_id: si-02.06
implementation_level: organization
parameter_ids:
- si-02.06_odp
reference_links:
- '#si-2'
---

# Summary

Remove previous versions of {{ insert: param, si-02.06_odp }} after updated versions have been installed.

# Statement

Remove previous versions of {{ insert: param, si-02.06_odp }} after updated versions have been installed.

# Guidance

Previous versions of software or firmware components that are not removed from the system after updates have been installed may be exploited by adversaries. Some products may automatically remove previous versions of software and firmware from the system.

# Parameters

- `si-02.06_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
