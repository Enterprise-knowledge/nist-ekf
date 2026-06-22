---
type: control_enhancement
title: CM-8.6 - Assessed Configurations and Approved Deviations
description: Include assessed component configurations and any approved deviations to current deployed configurations
  in the system component inventory.
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
  description: CM-8.6 - Assessed Configurations and Approved Deviations is part of its parent SP 800-53 structure.
- name: CM-8 - System Component Inventory
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-8.md
  relation: enhances
  description: CM-8.6 enhances base control CM-8.
nist_id: CM-8.6
sort_id: cm-08.06
implementation_level: organization
parameter_ids: []
reference_links:
- '#cm-8'
---

# Summary

Include assessed component configurations and any approved deviations to current deployed configurations in the system component inventory.

# Statement

Include assessed component configurations and any approved deviations to current deployed configurations in the system component inventory.

# Guidance

Assessed configurations and approved deviations focus on configuration settings established by organizations for system components, the specific components that have been assessed to determine compliance with the required configuration settings, and any approved deviations from established configuration settings.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
