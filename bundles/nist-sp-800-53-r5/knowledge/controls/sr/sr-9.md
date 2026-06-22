---
type: control
title: SR-9 - Tamper Resistance and Detection
description: Implement a tamper protection program for the system, system component, or system service.
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control
- sr
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/sr.md
  relation: part_of
  description: SR-9 - Tamper Resistance and Detection is part of its parent SP 800-53 structure.
- name: SR-9.1 - Multiple Stages of System Development Life Cycle
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sr/sr-9.1.md
  relation: has_enhancement
  description: SR-9 has enhancement SR-9.1.
nist_id: SR-9
sort_id: sr-09
implementation_level: organization
parameter_ids: []
reference_links:
- '#15a95e24-65b6-4686-bc18-90855a10457d'
- '#pe-3'
- '#pm-30'
- '#sa-15'
- '#si-4'
- '#si-7'
- '#sr-3'
- '#sr-4'
- '#sr-5'
- '#sr-10'
- '#sr-11'
---

# Summary

Implement a tamper protection program for the system, system component, or system service.

# Statement

Implement a tamper protection program for the system, system component, or system service.

# Guidance

Anti-tamper technologies, tools, and techniques provide a level of protection for systems, system components, and services against many threats, including reverse engineering, modification, and substitution. Strong identification combined with tamper resistance and/or tamper detection is essential to protecting systems and components during distribution and when in use.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
