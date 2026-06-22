---
type: control_enhancement
title: CP-9.1 - Testing for Reliability and Integrity
description: 'Test backup information {{ insert: param, cp-9.1_prm_1 }} to verify media reliability and information
  integrity.'
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
- cp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-9.md
  relation: part_of
  description: CP-9.1 - Testing for Reliability and Integrity is part of its parent SP 800-53 structure.
- name: CP-9 - System Backup
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-9.md
  relation: enhances
  description: CP-9.1 enhances base control CP-9.
nist_id: CP-9.1
sort_id: cp-09.01
implementation_level: organization
parameter_ids:
- cp-9.1_prm_1
- cp-09.01_odp.01
- cp-09.01_odp.02
reference_links:
- '#cp-9'
- '#cp-4'
---

# Summary

Test backup information {{ insert: param, cp-9.1_prm_1 }} to verify media reliability and information integrity.

# Statement

Test backup information {{ insert: param, cp-9.1_prm_1 }} to verify media reliability and information integrity.

# Guidance

Organizations need assurance that backup information can be reliably retrieved. Reliability pertains to the systems and system components where the backup information is stored, the operations used to retrieve the information, and the integrity of the information being retrieved. Independent and specialized tests can be used for each of the aspects of reliability. For example, decrypting and transporting (or transmitting) a random sample of backup files from the alternate storage or backup site and comparing the information to the same information at the primary processing site can provide such assurance.

# Parameters

- `cp-9.1_prm_1`
- `cp-09.01_odp.01`
- `cp-09.01_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
