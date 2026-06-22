---
type: control_enhancement
title: IA-8.1 - Acceptance of PIV Credentials from Other Agencies
description: Accept and electronically verify Personal Identity Verification-compliant credentials from other federal
  agencies.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-8.md
  relation: part_of
  description: IA-8.1 - Acceptance of PIV Credentials from Other Agencies is part of its parent SP 800-53 structure.
- name: IA-8 - Identification and Authentication (Non-organizational Users)
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-8.md
  relation: enhances
  description: IA-8.1 enhances base control IA-8.
nist_id: IA-8.1
sort_id: ia-08.01
implementation_level: system
parameter_ids: []
reference_links:
- '#ia-8'
- '#pe-3'
---

# Summary

Accept and electronically verify Personal Identity Verification-compliant credentials from other federal agencies.

# Statement

Accept and electronically verify Personal Identity Verification-compliant credentials from other federal agencies.

# Guidance

Acceptance of Personal Identity Verification (PIV) credentials from other federal agencies applies to both logical and physical access control systems. PIV credentials are those credentials issued by federal agencies that conform to FIPS Publication 201 and supporting guidelines. The adequacy and reliability of PIV card issuers are addressed and authorized using [SP 800-79-2](#10963761-58fc-4b20-b3d6-b44a54daba03).

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
