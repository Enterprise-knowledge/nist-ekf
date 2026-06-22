---
type: control_enhancement
title: SI-3.10 - Malicious Code Analysis
description: SP 800-53 control SI-3.10.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-3.md
  relation: part_of
  description: SI-3.10 - Malicious Code Analysis is part of its parent SP 800-53 structure.
- name: SI-3 - Malicious Code Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-3.md
  relation: enhances
  description: SI-3.10 enhances base control SI-3.
nist_id: SI-3.10
sort_id: si-03.10
implementation_level: organization
parameter_ids:
- si-03.10_odp
reference_links:
- '#si-3'
---

# Summary

SP 800-53 control SI-3.10.

# Statement

No statement text was present in the OSCAL record.

# Guidance

The use of malicious code analysis tools provides organizations with a more in-depth understanding of adversary tradecraft (i.e., tactics, techniques, and procedures) and the functionality and purpose of specific instances of malicious code. Understanding the characteristics of malicious code facilitates effective organizational responses to current and future threats. Organizations can conduct malicious code analyses by employing reverse engineering techniques or by monitoring the behavior of executing code.

# Parameters

- `si-03.10_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
