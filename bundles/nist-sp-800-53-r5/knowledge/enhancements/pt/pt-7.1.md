---
type: control_enhancement
title: PT-7.1 - Social Security Numbers
description: 'When a system processes Social Security numbers:'
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
- pt
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-7.md
  relation: part_of
  description: PT-7.1 - Social Security Numbers is part of its parent SP 800-53 structure.
- name: PT-7 - Specific Categories of Personally Identifiable Information
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-7.md
  relation: enhances
  description: PT-7.1 enhances base control PT-7.
nist_id: PT-7.1
sort_id: pt-07.01
implementation_level: organization
parameter_ids: []
reference_links:
- '#pt-7'
- '#ia-4'
---

# Summary

When a system processes Social Security numbers:

# Statement

When a system processes Social Security numbers:

# Guidance

Federal law and policy establish specific requirements for organizations’ processing of Social Security numbers. Organizations take steps to eliminate unnecessary uses of Social Security numbers and other sensitive information and observe any particular requirements that apply.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
