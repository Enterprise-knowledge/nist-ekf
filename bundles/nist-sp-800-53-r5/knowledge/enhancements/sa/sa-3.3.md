---
type: control_enhancement
title: SA-3.3 - Technology Refresh
description: Plan for and implement a technology refresh schedule for the system throughout the system development
  life cycle.
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
  description: SA-3.3 - Technology Refresh is part of its parent SP 800-53 structure.
- name: SA-3 - System Development Life Cycle
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-3.md
  relation: enhances
  description: SA-3.3 enhances base control SA-3.
nist_id: SA-3.3
sort_id: sa-03.03
implementation_level: organization
parameter_ids: []
reference_links:
- '#sa-3'
- '#ma-6'
---

# Summary

Plan for and implement a technology refresh schedule for the system throughout the system development life cycle.

# Statement

Plan for and implement a technology refresh schedule for the system throughout the system development life cycle.

# Guidance

Technology refresh planning may encompass hardware, software, firmware, processes, personnel skill sets, suppliers, service providers, and facilities. The use of obsolete or nearing obsolete technology may increase the security and privacy risks associated with unsupported components, counterfeit or repurposed components, components unable to implement security or privacy requirements, slow or inoperable components, components from untrusted sources, inadvertent personnel error, or increased complexity. Technology refreshes typically occur during the operations and maintenance stage of the system development life cycle.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
