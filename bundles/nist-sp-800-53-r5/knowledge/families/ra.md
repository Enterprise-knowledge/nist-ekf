---
type: control_family
title: RA - Risk Assessment
description: SP 800-53 control family for Risk Assessment.
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
- ra
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
- name: RA-1 - Policy and Procedures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-1.md
  relation: contains
  description: The family contains control RA-1.
- name: RA-2 - Security Categorization
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-2.md
  relation: contains
  description: The family contains control RA-2.
- name: RA-3 - Risk Assessment
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-3.md
  relation: contains
  description: The family contains control RA-3.
- name: RA-4 - Risk Assessment Update
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-4.md
  relation: contains
  description: The family contains control RA-4.
- name: RA-5 - Vulnerability Monitoring and Scanning
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-5.md
  relation: contains
  description: The family contains control RA-5.
- name: RA-6 - Technical Surveillance Countermeasures Survey
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-6.md
  relation: contains
  description: The family contains control RA-6.
- name: RA-7 - Risk Response
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-7.md
  relation: contains
  description: The family contains control RA-7.
- name: RA-8 - Privacy Impact Assessments
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-8.md
  relation: contains
  description: The family contains control RA-8.
- name: RA-9 - Criticality Analysis
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-9.md
  relation: contains
  description: The family contains control RA-9.
- name: RA-10 - Threat Hunting
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-10.md
  relation: contains
  description: The family contains control RA-10.
nist_id: RA
base_control_count: 10
control_enhancement_count: 16
---

# Summary

The Risk Assessment family contains 10 base controls and 16 control enhancements in the NIST OSCAL catalog.

# Controls

- [RA-1 - Policy and Procedures](../controls/ra/ra-1.md) - SP 800-53 control RA-1.
- [RA-2 - Security Categorization](../controls/ra/ra-2.md) - SP 800-53 control RA-2.
- [RA-3 - Risk Assessment](../controls/ra/ra-3.md) - SP 800-53 control RA-3.
- [RA-4 - Risk Assessment Update](../controls/ra/ra-4.md) - SP 800-53 control RA-4.
- [RA-5 - Vulnerability Monitoring and Scanning](../controls/ra/ra-5.md) - SP 800-53 control RA-5.
- [RA-6 - Technical Surveillance Countermeasures Survey](../controls/ra/ra-6.md) - Employ a technical surveillance countermeasures survey at {{ insert: param, ra-06_odp.01 }} {{ insert: param, ra-06_odp.02 }}.
- [RA-7 - Risk Response](../controls/ra/ra-7.md) - Respond to findings from security and privacy assessments, monitoring, and audits in accordance with organizational risk tolerance.
- [RA-8 - Privacy Impact Assessments](../controls/ra/ra-8.md) - Conduct privacy impact assessments for systems, programs, or other activities before:
- [RA-9 - Criticality Analysis](../controls/ra/ra-9.md) - Identify critical system components and functions by performing a criticality analysis for {{ insert: param, ra-09_odp.01 }} at {{ insert: param, ra-09_odp.02 }}.
- [RA-10 - Threat Hunting](../controls/ra/ra-10.md) - SP 800-53 control RA-10.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
