---
type: control_enhancement
title: SA-3.1 - Manage Preproduction Environment
description: Protect system preproduction environments commensurate with risk throughout the system development
  life cycle for the system, system component, or system service.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-3.md
  relation: part_of
  description: SA-3.1 - Manage Preproduction Environment is part of its parent SP 800-53 structure.
- name: SA-3 - System Development Life Cycle
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-3.md
  relation: enhances
  description: SA-3.1 enhances base control SA-3.
nist_id: SA-3.1
sort_id: sa-03.01
implementation_level: organization
parameter_ids: []
reference_links:
- '#sa-3'
- '#cm-2'
- '#cm-4'
- '#ra-3'
- '#ra-9'
- '#sa-4'
---

# Summary

Protect system preproduction environments commensurate with risk throughout the system development life cycle for the system, system component, or system service.

# Statement

Protect system preproduction environments commensurate with risk throughout the system development life cycle for the system, system component, or system service.

# Guidance

The preproduction environment includes development, test, and integration environments. The program protection planning processes established by the Department of Defense are examples of managing the preproduction environment for defense contractors. Criticality analysis and the application of controls on developers also contribute to a more secure system development environment.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
