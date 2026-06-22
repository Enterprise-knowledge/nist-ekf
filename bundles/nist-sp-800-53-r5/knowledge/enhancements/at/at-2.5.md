---
type: control_enhancement
title: AT-2.5 - Advanced Persistent Threat
description: Provide literacy training on the advanced persistent threat.
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
- at
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/at/at-2.md
  relation: part_of
  description: AT-2.5 - Advanced Persistent Threat is part of its parent SP 800-53 structure.
- name: AT-2 - Literacy Training and Awareness
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/at/at-2.md
  relation: enhances
  description: AT-2.5 enhances base control AT-2.
nist_id: AT-2.5
sort_id: at-02.05
implementation_level: organization
parameter_ids: []
reference_links:
- '#at-2'
---

# Summary

Provide literacy training on the advanced persistent threat.

# Statement

Provide literacy training on the advanced persistent threat.

# Guidance

An effective way to detect advanced persistent threats (APT) and to preclude successful attacks is to provide specific literacy training for individuals. Threat literacy training includes educating individuals on the various ways that APTs can infiltrate the organization (e.g., through websites, emails, advertisement pop-ups, articles, and social engineering). Effective training includes techniques for recognizing suspicious emails, use of removable systems in non-secure settings, and the potential targeting of individuals at home.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
