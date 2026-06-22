---
type: control_enhancement
title: SA-9.6 - Organization-controlled Cryptographic Keys
description: Maintain exclusive control of cryptographic keys for encrypted material stored or transmitted through
  an external system.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-9.md
  relation: part_of
  description: SA-9.6 - Organization-controlled Cryptographic Keys is part of its parent SP 800-53 structure.
- name: SA-9 - External System Services
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-9.md
  relation: enhances
  description: SA-9.6 enhances base control SA-9.
nist_id: SA-9.6
sort_id: sa-09.06
implementation_level: organization
parameter_ids: []
reference_links:
- '#sa-9'
- '#sc-12'
- '#sc-13'
- '#si-4'
---

# Summary

Maintain exclusive control of cryptographic keys for encrypted material stored or transmitted through an external system.

# Statement

Maintain exclusive control of cryptographic keys for encrypted material stored or transmitted through an external system.

# Guidance

Maintaining exclusive control of cryptographic keys in an external system prevents decryption of organizational data by external system staff. Organizational control of cryptographic keys can be implemented by encrypting and decrypting data inside the organization as data is sent to and received from the external system or by employing a component that permits encryption and decryption functions to be local to the external system but allows exclusive organizational access to the encryption keys.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
