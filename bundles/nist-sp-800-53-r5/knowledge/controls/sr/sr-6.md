---
type: control
title: SR-6 - Supplier Assessments and Reviews
description: 'Assess and review the supply chain-related risks associated with suppliers or contractors and the
  system, system component, or system service they provide {{ insert: param, sr-06_odp }}.'
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control
- sr
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/sr.md
  relation: part_of
  description: SR-6 - Supplier Assessments and Reviews is part of its parent SP 800-53 structure.
- name: SR-6.1 - Testing and Analysis
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sr/sr-6.1.md
  relation: has_enhancement
  description: SR-6 has enhancement SR-6.1.
nist_id: SR-6
sort_id: sr-06
implementation_level: organization
parameter_ids:
- sr-06_odp
reference_links:
- '#4ff10ed3-d8fe-4246-99e3-443045e27482'
- '#0f963c17-ab5a-432a-a867-91eac550309b'
- '#21caa535-1154-4369-ba7b-32c309fee0f7'
- '#863caf2a-978a-4260-9e8d-4a8929bce40c'
- '#15a95e24-65b6-4686-bc18-90855a10457d'
- '#678e3d6c-150b-4393-aec5-6e3481eb1e00'
- '#eea3c092-42ed-4382-a6f4-1adadef01b9d'
- '#7c37a38d-21d7-40d8-bc3d-b5e27eac17e1'
- '#a295ca19-8c75-4b4c-8800-98024732e181'
- '#08b07465-dbdc-48d6-8a0b-37279602ac16'
- '#e8e84963-14fc-4c3a-be05-b412a5d37cd2'
- '#e24b06cc-9129-4998-a76a-65c3d7a576ba'
- '#38ff38f0-1366-4f50-a4c9-26a39aacee16'
- '#sr-3'
- '#sr-5'
---

# Summary

Assess and review the supply chain-related risks associated with suppliers or contractors and the system, system component, or system service they provide {{ insert: param, sr-06_odp }}.

# Statement

Assess and review the supply chain-related risks associated with suppliers or contractors and the system, system component, or system service they provide {{ insert: param, sr-06_odp }}.

# Guidance

An assessment and review of supplier risk includes security and supply chain risk management processes, foreign ownership, control or influence (FOCI), and the ability of the supplier to effectively assess subordinate second-tier and third-tier suppliers and contractors. The reviews may be conducted by the organization or by an independent third party. The reviews consider documented processes, documented controls, all-source intelligence, and publicly available information related to the supplier or contractor. Organizations can use open-source information to monitor for indications of stolen information, poor development and quality control practices, information spillage, or counterfeits. In some cases, it may be appropriate or required to share assessment and review results with other organizations in accordance with any applicable rules, policies, or inter-organizational agreements or contracts.

# Parameters

- `sr-06_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
