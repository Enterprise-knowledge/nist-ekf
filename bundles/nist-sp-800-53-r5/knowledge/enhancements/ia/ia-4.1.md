---
type: control_enhancement
title: IA-4.1 - Prohibit Account Identifiers as Public Identifiers
description: Prohibit the use of system account identifiers that are the same as public identifiers for individual
  accounts.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-4.md
  relation: part_of
  description: IA-4.1 - Prohibit Account Identifiers as Public Identifiers is part of its parent SP 800-53 structure.
- name: IA-4 - Identifier Management
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-4.md
  relation: enhances
  description: IA-4.1 enhances base control IA-4.
nist_id: IA-4.1
sort_id: ia-04.01
implementation_level: organization
parameter_ids: []
reference_links:
- '#ia-4'
- '#at-2'
- '#pt-7'
---

# Summary

Prohibit the use of system account identifiers that are the same as public identifiers for individual accounts.

# Statement

Prohibit the use of system account identifiers that are the same as public identifiers for individual accounts.

# Guidance

Prohibiting account identifiers as public identifiers applies to any publicly disclosed account identifier used for communication such as, electronic mail and instant messaging. Prohibiting the use of systems account identifiers that are the same as some public identifier, such as the individual identifier section of an electronic mail address, makes it more difficult for adversaries to guess user identifiers. Prohibiting account identifiers as public identifiers without the implementation of other supporting controls only complicates guessing of identifiers. Additional protections are required for authenticators and credentials to protect the account.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
