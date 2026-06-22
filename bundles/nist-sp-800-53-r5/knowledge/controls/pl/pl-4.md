---
type: control
title: PL-4 - Rules of Behavior
description: SP 800-53 control PL-4.
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
- pl
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/pl.md
  relation: part_of
  description: PL-4 - Rules of Behavior is part of its parent SP 800-53 structure.
- name: PL-4.1 - Social Media and External Site/Application Usage Restrictions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pl/pl-4.1.md
  relation: has_enhancement
  description: PL-4 has enhancement PL-4.1.
nist_id: PL-4
sort_id: pl-04
implementation_level: organization
parameter_ids:
- pl-04_odp.01
- pl-04_odp.02
- pl-04_odp.03
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#30eb758a-2707-4bca-90ad-949a74d4eb16'
- '#ac-2'
- '#ac-6'
- '#ac-8'
- '#ac-9'
- '#ac-17'
- '#ac-18'
- '#ac-19'
- '#ac-20'
- '#at-2'
- '#at-3'
- '#cm-11'
- '#ia-2'
- '#ia-4'
- '#ia-5'
- '#mp-7'
- '#ps-6'
- '#ps-8'
- '#sa-5'
- '#si-12'
---

# Summary

SP 800-53 control PL-4.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Rules of behavior represent a type of access agreement for organizational users. Other types of access agreements include nondisclosure agreements, conflict-of-interest agreements, and acceptable use agreements (see [PS-6](#ps-6) ). Organizations consider rules of behavior based on individual user roles and responsibilities and differentiate between rules that apply to privileged users and rules that apply to general users. Establishing rules of behavior for some types of non-organizational users, including individuals who receive information from federal systems, is often not feasible given the large number of such users and the limited nature of their interactions with the systems. Rules of behavior for organizational and non-organizational users can also be established in [AC-8](#ac-8) . The related controls section provides a list of controls that are relevant to organizational rules of behavior. [PL-4b](#pl-4_smt.b) , the documented acknowledgment portion of the control, may be satisfied by the literacy training and awareness and role-based training programs conducted by organizations if such training includes rules of behavior. Documented acknowledgements for rules of behavior include electronic or physical signatures and electronic agreement check boxes or radio buttons.

# Parameters

- `pl-04_odp.01`
- `pl-04_odp.02`
- `pl-04_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
