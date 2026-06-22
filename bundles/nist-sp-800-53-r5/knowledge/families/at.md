---
type: control_family
title: AT - Awareness and Training
description: SP 800-53 control family for Awareness and Training.
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control-family
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
- name: The Controls
  path: /bundles/nist-sp-800-53-r5/knowledge/sections/controls.md
  relation: part_of
  description: This family is part of the controls section.
- name: AT-1 - Policy and Procedures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/at/at-1.md
  relation: contains
  description: The family contains control AT-1.
- name: AT-2 - Literacy Training and Awareness
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/at/at-2.md
  relation: contains
  description: The family contains control AT-2.
- name: AT-3 - Role-based Training
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/at/at-3.md
  relation: contains
  description: The family contains control AT-3.
- name: AT-4 - Training Records
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/at/at-4.md
  relation: contains
  description: The family contains control AT-4.
- name: AT-5 - Contacts with Security Groups and Associations
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/at/at-5.md
  relation: contains
  description: The family contains control AT-5.
- name: AT-6 - Training Feedback
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/at/at-6.md
  relation: contains
  description: The family contains control AT-6.
nist_id: AT
base_control_count: 6
control_enhancement_count: 11
---

# Summary

The Awareness and Training family contains 6 base controls and 11 control enhancements in the NIST OSCAL catalog.

# Controls

- [AT-1 - Policy and Procedures](../controls/at/at-1.md) - SP 800-53 control AT-1.
- [AT-2 - Literacy Training and Awareness](../controls/at/at-2.md) - SP 800-53 control AT-2.
- [AT-3 - Role-based Training](../controls/at/at-3.md) - SP 800-53 control AT-3.
- [AT-4 - Training Records](../controls/at/at-4.md) - SP 800-53 control AT-4.
- [AT-5 - Contacts with Security Groups and Associations](../controls/at/at-5.md) - SP 800-53 control AT-5.
- [AT-6 - Training Feedback](../controls/at/at-6.md) - Provide feedback on organizational training results to the following personnel {{ insert: param, at-06_odp.01 }}: {{ insert: param, at-06_odp.02 }}.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
