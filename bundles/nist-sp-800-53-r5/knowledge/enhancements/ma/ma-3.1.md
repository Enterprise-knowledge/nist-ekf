---
type: control_enhancement
title: MA-3.1 - Inspect Tools
description: Inspect the maintenance tools used by maintenance personnel for improper or unauthorized modifications.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-3.md
  relation: part_of
  description: MA-3.1 - Inspect Tools is part of its parent SP 800-53 structure.
- name: MA-3 - Maintenance Tools
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-3.md
  relation: enhances
  description: MA-3.1 enhances base control MA-3.
nist_id: MA-3.1
sort_id: ma-03.01
implementation_level: organization
parameter_ids: []
reference_links:
- '#ma-3'
- '#si-7'
---

# Summary

Inspect the maintenance tools used by maintenance personnel for improper or unauthorized modifications.

# Statement

Inspect the maintenance tools used by maintenance personnel for improper or unauthorized modifications.

# Guidance

Maintenance tools can be directly brought into a facility by maintenance personnel or downloaded from a vendor’s website. If, upon inspection of the maintenance tools, organizations determine that the tools have been modified in an improper manner or the tools contain malicious code, the incident is handled consistent with organizational policies and procedures for incident handling.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
