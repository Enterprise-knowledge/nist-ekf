---
type: control_enhancement
title: CM-4.2 - Verification of Controls
description: After system changes, verify that the impacted controls are implemented correctly, operating as intended,
  and producing the desired outcome with regard to meeting the security and privacy requirements for the system.
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
- cm
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-4.md
  relation: part_of
  description: CM-4.2 - Verification of Controls is part of its parent SP 800-53 structure.
- name: CM-4 - Impact Analyses
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-4.md
  relation: enhances
  description: CM-4.2 enhances base control CM-4.
nist_id: CM-4.2
sort_id: cm-04.02
implementation_level: organization
parameter_ids: []
reference_links:
- '#cm-4'
- '#sa-11'
- '#sc-3'
- '#si-6'
---

# Summary

After system changes, verify that the impacted controls are implemented correctly, operating as intended, and producing the desired outcome with regard to meeting the security and privacy requirements for the system.

# Statement

After system changes, verify that the impacted controls are implemented correctly, operating as intended, and producing the desired outcome with regard to meeting the security and privacy requirements for the system.

# Guidance

Implementation in this context refers to installing changed code in the operational system that may have an impact on security or privacy controls.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
