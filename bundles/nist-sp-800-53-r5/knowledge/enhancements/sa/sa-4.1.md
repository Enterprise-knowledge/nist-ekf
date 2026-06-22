---
type: control_enhancement
title: SA-4.1 - Functional Properties of Controls
description: Require the developer of the system, system component, or system service to provide a description of
  the functional properties of the controls to be implemented.
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
- sa
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-4.md
  relation: part_of
  description: SA-4.1 - Functional Properties of Controls is part of its parent SP 800-53 structure.
- name: SA-4 - Acquisition Process
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-4.md
  relation: enhances
  description: SA-4.1 enhances base control SA-4.
nist_id: SA-4.1
sort_id: sa-04.01
implementation_level: organization
parameter_ids: []
reference_links:
- '#sa-4'
---

# Summary

Require the developer of the system, system component, or system service to provide a description of the functional properties of the controls to be implemented.

# Statement

Require the developer of the system, system component, or system service to provide a description of the functional properties of the controls to be implemented.

# Guidance

Functional properties of security and privacy controls describe the functionality (i.e., security or privacy capability, functions, or mechanisms) visible at the interfaces of the controls and specifically exclude functionality and data structures internal to the operation of the controls.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
