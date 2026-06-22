---
type: control_enhancement
title: SI-2.2 - Automated Flaw Remediation Status
description: 'Determine if system components have applicable security-relevant software and firmware updates installed
  using {{ insert: param, si-02.02_odp.01 }} {{ insert: param, si-02.02_odp.02 }}.'
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
- si
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-2.md
  relation: part_of
  description: SI-2.2 - Automated Flaw Remediation Status is part of its parent SP 800-53 structure.
- name: SI-2 - Flaw Remediation
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-2.md
  relation: enhances
  description: SI-2.2 enhances base control SI-2.
nist_id: SI-2.2
sort_id: si-02.02
implementation_level: organization
parameter_ids:
- si-02.02_odp.01
- si-02.02_odp.02
reference_links:
- '#si-2'
- '#ca-7'
- '#si-4'
---

# Summary

Determine if system components have applicable security-relevant software and firmware updates installed using {{ insert: param, si-02.02_odp.01 }} {{ insert: param, si-02.02_odp.02 }}.

# Statement

Determine if system components have applicable security-relevant software and firmware updates installed using {{ insert: param, si-02.02_odp.01 }} {{ insert: param, si-02.02_odp.02 }}.

# Guidance

Automated mechanisms can track and determine the status of known flaws for system components.

# Parameters

- `si-02.02_odp.01`
- `si-02.02_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
