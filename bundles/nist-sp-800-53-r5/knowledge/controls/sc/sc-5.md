---
type: control
title: SC-5 - Denial-of-service Protection
description: SP 800-53 control SC-5.
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
- sc
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/sc.md
  relation: part_of
  description: SC-5 - Denial-of-service Protection is part of its parent SP 800-53 structure.
- name: SC-5.1 - Restrict Ability to Attack Other Systems
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-5.1.md
  relation: has_enhancement
  description: SC-5 has enhancement SC-5.1.
- name: SC-5.2 - Capacity, Bandwidth, and Redundancy
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-5.2.md
  relation: has_enhancement
  description: SC-5 has enhancement SC-5.2.
- name: SC-5.3 - Detection and Monitoring
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-5.3.md
  relation: has_enhancement
  description: SC-5 has enhancement SC-5.3.
nist_id: SC-5
sort_id: sc-05
implementation_level: system
parameter_ids:
- sc-05_odp.01
- sc-05_odp.02
- sc-05_odp.03
reference_links:
- '#f5edfe51-d1f2-422e-9b27-5d0e90b49c72'
- '#cp-2'
- '#ir-4'
- '#sc-6'
- '#sc-7'
- '#sc-40'
---

# Summary

SP 800-53 control SC-5.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Denial-of-service events may occur due to a variety of internal and external causes, such as an attack by an adversary or a lack of planning to support organizational needs with respect to capacity and bandwidth. Such attacks can occur across a wide range of network protocols (e.g., IPv4, IPv6). A variety of technologies are available to limit or eliminate the origination and effects of denial-of-service events. For example, boundary protection devices can filter certain types of packets to protect system components on internal networks from being directly affected by or the source of denial-of-service attacks. Employing increased network capacity and bandwidth combined with service redundancy also reduces the susceptibility to denial-of-service events.

# Parameters

- `sc-05_odp.01`
- `sc-05_odp.02`
- `sc-05_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
