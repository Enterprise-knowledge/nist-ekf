---
type: control_enhancement
title: IA-3.3 - Dynamic Address Allocation
description: SP 800-53 control IA-3.3.
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
- ia
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-3.md
  relation: part_of
  description: IA-3.3 - Dynamic Address Allocation is part of its parent SP 800-53 structure.
- name: IA-3 - Device Identification and Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-3.md
  relation: enhances
  description: IA-3.3 enhances base control IA-3.
nist_id: IA-3.3
sort_id: ia-03.03
implementation_level: organization
parameter_ids:
- ia-3.3_prm_1
- ia-03.03_odp.01
- ia-03.03_odp.02
reference_links:
- '#ia-3'
- '#au-2'
---

# Summary

SP 800-53 control IA-3.3.

# Statement

No statement text was present in the OSCAL record.

# Guidance

The Dynamic Host Configuration Protocol (DHCP) is an example of a means by which clients can dynamically receive network address assignments.

# Parameters

- `ia-3.3_prm_1`
- `ia-03.03_odp.01`
- `ia-03.03_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
