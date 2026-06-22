---
type: control
title: IR-9 - Information Spillage Response
description: 'Respond to information spills by:'
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
- ir
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ir.md
  relation: part_of
  description: IR-9 - Information Spillage Response is part of its parent SP 800-53 structure.
- name: IR-9.1 - Responsible Personnel
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-9.1.md
  relation: has_enhancement
  description: IR-9 has enhancement IR-9.1.
- name: IR-9.2 - Training
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-9.2.md
  relation: has_enhancement
  description: IR-9 has enhancement IR-9.2.
- name: IR-9.3 - Post-spill Operations
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-9.3.md
  relation: has_enhancement
  description: IR-9 has enhancement IR-9.3.
- name: IR-9.4 - Exposure to Unauthorized Personnel
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-9.4.md
  relation: has_enhancement
  description: IR-9 has enhancement IR-9.4.
nist_id: IR-9
sort_id: ir-09
implementation_level: organization
parameter_ids:
- ir-09_odp.01
- ir-09_odp.02
- ir-09_odp.03
reference_links:
- '#cp-2'
- '#ir-6'
- '#pm-26'
- '#pm-27'
- '#pt-2'
- '#pt-3'
- '#pt-7'
- '#ra-7'
---

# Summary

Respond to information spills by:

# Statement

Respond to information spills by:

# Guidance

Information spillage refers to instances where information is placed on systems that are not authorized to process such information. Information spills occur when information that is thought to be a certain classification or impact level is transmitted to a system and subsequently is determined to be of a higher classification or impact level. At that point, corrective action is required. The nature of the response is based on the classification or impact level of the spilled information, the security capabilities of the system, the specific nature of the contaminated storage media, and the access authorizations of individuals with authorized access to the contaminated system. The methods used to communicate information about the spill after the fact do not involve methods directly associated with the actual spill to minimize the risk of further spreading the contamination before such contamination is isolated and eradicated.

# Parameters

- `ir-09_odp.01`
- `ir-09_odp.02`
- `ir-09_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
