---
type: control_enhancement
title: AC-6.4 - Separate Processing Domains
description: Provide separate processing domains to enable finer-grained allocation of user privileges.
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
- ac
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-6.md
  relation: part_of
  description: AC-6.4 - Separate Processing Domains is part of its parent SP 800-53 structure.
- name: AC-6 - Least Privilege
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-6.md
  relation: enhances
  description: AC-6.4 enhances base control AC-6.
nist_id: AC-6.4
sort_id: ac-06.04
implementation_level: organization
parameter_ids: []
reference_links:
- '#ac-6'
- '#ac-4'
- '#sc-2'
- '#sc-3'
- '#sc-30'
- '#sc-32'
- '#sc-39'
---

# Summary

Provide separate processing domains to enable finer-grained allocation of user privileges.

# Statement

Provide separate processing domains to enable finer-grained allocation of user privileges.

# Guidance

Providing separate processing domains for finer-grained allocation of user privileges includes using virtualization techniques to permit additional user privileges within a virtual machine while restricting privileges to other virtual machines or to the underlying physical machine, implementing separate physical domains, and employing hardware or software domain separation mechanisms.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
