---
type: control_enhancement
title: IA-2.12 - Acceptance of PIV Credentials
description: Accept and electronically verify Personal Identity Verification-compliant credentials.
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
  description: IA-2.12 - Acceptance of PIV Credentials is part of its parent SP 800-53 structure.
- name: IA-2 - Identification and Authentication (Organizational Users)
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-2.md
  relation: enhances
  description: IA-2.12 enhances base control IA-2.
nist_id: IA-2.12
sort_id: ia-02.12
implementation_level: system
parameter_ids: []
reference_links:
- '#ia-2'
---

# Summary

Accept and electronically verify Personal Identity Verification-compliant credentials.

# Statement

Accept and electronically verify Personal Identity Verification-compliant credentials.

# Guidance

Acceptance of Personal Identity Verification (PIV)-compliant credentials applies to organizations implementing logical access control and physical access control systems. PIV-compliant credentials are those credentials issued by federal agencies that conform to FIPS Publication 201 and supporting guidance documents. The adequacy and reliability of PIV card issuers are authorized using [SP 800-79-2](#10963761-58fc-4b20-b3d6-b44a54daba03) . Acceptance of PIV-compliant credentials includes derived PIV credentials, the use of which is addressed in [SP 800-166](#e8552d48-cf41-40aa-8b06-f45f7fb4706c) . The DOD Common Access Card (CAC) is an example of a PIV credential.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
