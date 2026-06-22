---
type: control_enhancement
title: SA-4.9 - Functions, Ports, Protocols, and Services in Use
description: Require the developer of the system, system component, or system service to identify the functions,
  ports, protocols, and services intended for organizational use.
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
  description: SA-4.9 - Functions, Ports, Protocols, and Services in Use is part of its parent SP 800-53 structure.
- name: SA-4 - Acquisition Process
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-4.md
  relation: enhances
  description: SA-4.9 enhances base control SA-4.
nist_id: SA-4.9
sort_id: sa-04.09
implementation_level: organization
parameter_ids: []
reference_links:
- '#sa-4'
- '#cm-7'
- '#sa-9'
---

# Summary

Require the developer of the system, system component, or system service to identify the functions, ports, protocols, and services intended for organizational use.

# Statement

Require the developer of the system, system component, or system service to identify the functions, ports, protocols, and services intended for organizational use.

# Guidance

The identification of functions, ports, protocols, and services early in the system development life cycle (e.g., during the initial requirements definition and design stages) allows organizations to influence the design of the system, system component, or system service. This early involvement in the system development life cycle helps organizations avoid or minimize the use of functions, ports, protocols, or services that pose unnecessarily high risks and understand the trade-offs involved in blocking specific ports, protocols, or services or requiring system service providers to do so. Early identification of functions, ports, protocols, and services avoids costly retrofitting of controls after the system, component, or system service has been implemented. [SA-9](#sa-9) describes the requirements for external system services. Organizations identify which functions, ports, protocols, and services are provided from external sources.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
