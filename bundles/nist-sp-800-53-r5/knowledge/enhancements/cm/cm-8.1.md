---
type: control_enhancement
title: CM-8.1 - Updates During Installation and Removal
description: Update the inventory of system components as part of component installations, removals, and system
  updates.
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
- cm
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-8.md
  relation: part_of
  description: CM-8.1 - Updates During Installation and Removal is part of its parent SP 800-53 structure.
- name: CM-8 - System Component Inventory
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-8.md
  relation: enhances
  description: CM-8.1 enhances base control CM-8.
nist_id: CM-8.1
sort_id: cm-08.01
implementation_level: organization
parameter_ids: []
reference_links:
- '#cm-8'
- '#pm-16'
---

# Summary

Update the inventory of system components as part of component installations, removals, and system updates.

# Statement

Update the inventory of system components as part of component installations, removals, and system updates.

# Guidance

Organizations can improve the accuracy, completeness, and consistency of system component inventories if the inventories are updated as part of component installations or removals or during general system updates. If inventories are not updated at these key times, there is a greater likelihood that the information will not be appropriately captured and documented. System updates include hardware, software, and firmware components.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
