---
type: control
title: SR-8 - Notification Agreements
description: 'Establish agreements and procedures with entities involved in the supply chain for the system, system
  component, or system service for the {{ insert: param, sr-08_odp.01 }}.'
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
  description: SR-8 - Notification Agreements is part of its parent SP 800-53 structure.
nist_id: SR-8
sort_id: sr-08
implementation_level: organization
parameter_ids:
- sr-08_odp.01
- sr-08_odp.02
reference_links:
- '#4ff10ed3-d8fe-4246-99e3-443045e27482'
- '#0f963c17-ab5a-432a-a867-91eac550309b'
- '#21caa535-1154-4369-ba7b-32c309fee0f7'
- '#863caf2a-978a-4260-9e8d-4a8929bce40c'
- '#08b07465-dbdc-48d6-8a0b-37279602ac16'
- '#e8e84963-14fc-4c3a-be05-b412a5d37cd2'
- '#e24b06cc-9129-4998-a76a-65c3d7a576ba'
- '#ir-4'
- '#ir-6'
- '#ir-8'
---

# Summary

Establish agreements and procedures with entities involved in the supply chain for the system, system component, or system service for the {{ insert: param, sr-08_odp.01 }}.

# Statement

Establish agreements and procedures with entities involved in the supply chain for the system, system component, or system service for the {{ insert: param, sr-08_odp.01 }}.

# Guidance

The establishment of agreements and procedures facilitates communications among supply chain entities. Early notification of compromises and potential compromises in the supply chain that can potentially adversely affect or have adversely affected organizational systems or system components is essential for organizations to effectively respond to such incidents. The results of assessments or audits may include open-source information that contributed to a decision or result and could be used to help the supply chain entity resolve a concern or improve its processes.

# Parameters

- `sr-08_odp.01`
- `sr-08_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
