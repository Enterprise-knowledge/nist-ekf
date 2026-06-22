---
type: control_enhancement
title: SR-4.3 - Validate as Genuine and Not Altered
description: 'Employ the following controls to validate that the system or system component received is genuine
  and has not been altered: {{ insert: param, sr-4.3_prm_1 }}.'
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-4.md
  relation: part_of
  description: SR-4.3 - Validate as Genuine and Not Altered is part of its parent SP 800-53 structure.
- name: SR-4 - Provenance
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-4.md
  relation: enhances
  description: SR-4.3 enhances base control SR-4.
nist_id: SR-4.3
sort_id: sr-04.03
implementation_level: organization
parameter_ids:
- sr-4.3_prm_1
- sr-04.03_odp.01
- sr-04.03_odp.02
reference_links:
- '#sr-4'
- '#at-3'
- '#sr-9'
- '#sr-10'
- '#sr-11'
---

# Summary

Employ the following controls to validate that the system or system component received is genuine and has not been altered: {{ insert: param, sr-4.3_prm_1 }}.

# Statement

Employ the following controls to validate that the system or system component received is genuine and has not been altered: {{ insert: param, sr-4.3_prm_1 }}.

# Guidance

For many systems and system components, especially hardware, there are technical means to determine if the items are genuine or have been altered, including optical and nanotechnology tagging, physically unclonable functions, side-channel analysis, cryptographic hash verifications or digital signatures, and visible anti-tamper labels or stickers. Controls can also include monitoring for out of specification performance, which can be an indicator of tampering or counterfeits. Organizations may leverage supplier and contractor processes for validating that a system or component is genuine and has not been altered and for replacing a suspect system or component. Some indications of tampering may be visible and addressable before accepting delivery, such as inconsistent packaging, broken seals, and incorrect labels. When a system or system component is suspected of being altered or counterfeit, the supplier, contractor, or original equipment manufacturer may be able to replace the item or provide a forensic capability to determine the origin of the counterfeit or altered item. Organizations can provide training to personnel on how to identify suspicious system or component deliveries.

# Parameters

- `sr-4.3_prm_1`
- `sr-04.03_odp.01`
- `sr-04.03_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
