---
type: control_enhancement
title: AC-4.8 - Security and Privacy Policy Filters
description: SP 800-53 control AC-4.8.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-4.md
  relation: part_of
  description: AC-4.8 - Security and Privacy Policy Filters is part of its parent SP 800-53 structure.
- name: AC-4 - Information Flow Enforcement
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ac/ac-4.md
  relation: enhances
  description: AC-4.8 enhances base control AC-4.
nist_id: AC-4.8
sort_id: ac-04.08
implementation_level: system
parameter_ids:
- ac-4.8_prm_1
- ac-4.8_prm_2
- ac-4.8_prm_4
- ac-04.08_odp.01
- ac-04.08_odp.02
- ac-04.08_odp.03
- ac-04.08_odp.04
- ac-04.08_odp.05
- ac-04.08_odp.06
- ac-04.08_odp.07
reference_links:
- '#ac-4'
---

# Summary

SP 800-53 control AC-4.8.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Organization-defined security or privacy policy filters can address data structures and content. For example, security or privacy policy filters for data structures can check for maximum file lengths, maximum field sizes, and data/file types (for structured and unstructured data). Security or privacy policy filters for data content can check for specific words, enumerated values or data value ranges, and hidden content. Structured data permits the interpretation of data content by applications. Unstructured data refers to digital information without a data structure or with a data structure that does not facilitate the development of rule sets to address the impact or classification level of the information conveyed by the data or the flow enforcement decisions. Unstructured data consists of bitmap objects that are inherently non-language-based (i.e., image, video, or audio files) and textual objects that are based on written or printed languages. Organizations can implement more than one security or privacy policy filter to meet information flow control objectives.

# Parameters

- `ac-4.8_prm_1`
- `ac-4.8_prm_2`
- `ac-4.8_prm_4`
- `ac-04.08_odp.01`
- `ac-04.08_odp.02`
- `ac-04.08_odp.03`
- `ac-04.08_odp.04`
- `ac-04.08_odp.05`
- `ac-04.08_odp.06`
- `ac-04.08_odp.07`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
