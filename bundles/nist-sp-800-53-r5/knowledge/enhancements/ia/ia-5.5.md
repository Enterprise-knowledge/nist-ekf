---
type: control_enhancement
title: IA-5.5 - Change Authenticators Prior to Delivery
description: Require developers and installers of system components to provide unique authenticators or change default
  authenticators prior to delivery and installation.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-5.md
  relation: part_of
  description: IA-5.5 - Change Authenticators Prior to Delivery is part of its parent SP 800-53 structure.
- name: IA-5 - Authenticator Management
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ia/ia-5.md
  relation: enhances
  description: IA-5.5 enhances base control IA-5.
nist_id: IA-5.5
sort_id: ia-05.05
implementation_level: organization
parameter_ids: []
reference_links:
- '#ia-5'
---

# Summary

Require developers and installers of system components to provide unique authenticators or change default authenticators prior to delivery and installation.

# Statement

Require developers and installers of system components to provide unique authenticators or change default authenticators prior to delivery and installation.

# Guidance

Changing authenticators prior to the delivery and installation of system components extends the requirement for organizations to change default authenticators upon system installation by requiring developers and/or installers to provide unique authenticators or change default authenticators for system components prior to delivery and/or installation. However, it typically does not apply to developers of commercial off-the-shelf information technology products. Requirements for unique authenticators can be included in acquisition documents prepared by organizations when procuring systems or system components.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
