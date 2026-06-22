---
type: control_enhancement
title: MA-4.7 - Disconnect Verification
description: Verify session and network connection termination after the completion of nonlocal maintenance and
  diagnostic sessions.
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
- ma
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-4.md
  relation: part_of
  description: MA-4.7 - Disconnect Verification is part of its parent SP 800-53 structure.
- name: MA-4 - Nonlocal Maintenance
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-4.md
  relation: enhances
  description: MA-4.7 enhances base control MA-4.
nist_id: MA-4.7
sort_id: ma-04.07
implementation_level: system
parameter_ids: []
reference_links:
- '#ma-4'
- '#ac-12'
---

# Summary

Verify session and network connection termination after the completion of nonlocal maintenance and diagnostic sessions.

# Statement

Verify session and network connection termination after the completion of nonlocal maintenance and diagnostic sessions.

# Guidance

Verifying the termination of a connection once maintenance is completed ensures that connections established during nonlocal maintenance and diagnostic sessions have been terminated and are no longer available for use.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
