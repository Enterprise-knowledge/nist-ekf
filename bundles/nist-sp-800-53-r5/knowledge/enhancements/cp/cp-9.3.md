---
type: control_enhancement
title: CP-9.3 - Separate Storage for Critical Information
description: 'Store backup copies of {{ insert: param, cp-09.03_odp }} in a separate facility or in a fire rated
  container that is not collocated with the operational system.'
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
- cp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-9.md
  relation: part_of
  description: CP-9.3 - Separate Storage for Critical Information is part of its parent SP 800-53 structure.
- name: CP-9 - System Backup
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-9.md
  relation: enhances
  description: CP-9.3 enhances base control CP-9.
nist_id: CP-9.3
sort_id: cp-09.03
implementation_level: organization
parameter_ids:
- cp-09.03_odp
reference_links:
- '#cp-9'
- '#cm-2'
- '#cm-6'
- '#cm-8'
---

# Summary

Store backup copies of {{ insert: param, cp-09.03_odp }} in a separate facility or in a fire rated container that is not collocated with the operational system.

# Statement

Store backup copies of {{ insert: param, cp-09.03_odp }} in a separate facility or in a fire rated container that is not collocated with the operational system.

# Guidance

Separate storage for critical information applies to all critical information regardless of the type of backup storage media. Critical system software includes operating systems, middleware, cryptographic key management systems, and intrusion detection systems. Security-related information includes inventories of system hardware, software, and firmware components. Alternate storage sites, including geographically distributed architectures, serve as separate storage facilities for organizations. Organizations may provide separate storage by implementing automated backup processes at alternative storage sites (e.g., data centers). The General Services Administration (GSA) establishes standards and specifications for security and fire rated containers.

# Parameters

- `cp-09.03_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
