---
type: control_enhancement
title: IA-2.5 - Individual Authentication with Group Authentication
description: When shared accounts or authenticators are employed, require users to be individually authenticated
  before granting access to the shared accounts or resources.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-2.md
  relation: part_of
  description: IA-2.5 - Individual Authentication with Group Authentication is part of its parent SP 800-53 structure.
- name: IA-2 - Identification and Authentication (Organizational Users)
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-2.md
  relation: enhances
  description: IA-2.5 enhances base control IA-2.
nist_id: IA-2.5
sort_id: ia-02.05
implementation_level: organization
parameter_ids: []
reference_links:
- '#ia-2'
---

# Summary

When shared accounts or authenticators are employed, require users to be individually authenticated before granting access to the shared accounts or resources.

# Statement

When shared accounts or authenticators are employed, require users to be individually authenticated before granting access to the shared accounts or resources.

# Guidance

Individual authentication prior to shared group authentication mitigates the risk of using group accounts or authenticators.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
