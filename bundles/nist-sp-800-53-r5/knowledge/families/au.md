---
type: control_family
title: AU - Audit and Accountability
description: SP 800-53 control family for Audit and Accountability.
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
- au
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
- name: AU-1 - Policy and Procedures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-1.md
  relation: contains
  description: The family contains control AU-1.
- name: AU-2 - Event Logging
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-2.md
  relation: contains
  description: The family contains control AU-2.
- name: AU-3 - Content of Audit Records
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-3.md
  relation: contains
  description: The family contains control AU-3.
- name: AU-4 - Audit Log Storage Capacity
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-4.md
  relation: contains
  description: The family contains control AU-4.
- name: AU-5 - Response to Audit Logging Process Failures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-5.md
  relation: contains
  description: The family contains control AU-5.
- name: AU-6 - Audit Record Review, Analysis, and Reporting
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-6.md
  relation: contains
  description: The family contains control AU-6.
- name: AU-7 - Audit Record Reduction and Report Generation
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-7.md
  relation: contains
  description: The family contains control AU-7.
- name: AU-8 - Time Stamps
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-8.md
  relation: contains
  description: The family contains control AU-8.
- name: AU-9 - Protection of Audit Information
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-9.md
  relation: contains
  description: The family contains control AU-9.
- name: AU-10 - Non-repudiation
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-10.md
  relation: contains
  description: The family contains control AU-10.
- name: AU-11 - Audit Record Retention
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-11.md
  relation: contains
  description: The family contains control AU-11.
- name: AU-12 - Audit Record Generation
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-12.md
  relation: contains
  description: The family contains control AU-12.
- name: AU-13 - Monitoring for Information Disclosure
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-13.md
  relation: contains
  description: The family contains control AU-13.
- name: AU-14 - Session Audit
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-14.md
  relation: contains
  description: The family contains control AU-14.
- name: AU-15 - Alternate Audit Logging Capability
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-15.md
  relation: contains
  description: The family contains control AU-15.
- name: AU-16 - Cross-organizational Audit Logging
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-16.md
  relation: contains
  description: The family contains control AU-16.
nist_id: AU
base_control_count: 16
control_enhancement_count: 53
---

# Summary

The Audit and Accountability family contains 16 base controls and 53 control enhancements in the NIST OSCAL catalog.

# Controls

- [AU-1 - Policy and Procedures](../controls/au/au-1.md) - SP 800-53 control AU-1.
- [AU-2 - Event Logging](../controls/au/au-2.md) - SP 800-53 control AU-2.
- [AU-3 - Content of Audit Records](../controls/au/au-3.md) - Ensure that audit records contain information that establishes the following:
- [AU-4 - Audit Log Storage Capacity](../controls/au/au-4.md) - Allocate audit log storage capacity to accommodate {{ insert: param, au-04_odp }}.
- [AU-5 - Response to Audit Logging Process Failures](../controls/au/au-5.md) - SP 800-53 control AU-5.
- [AU-6 - Audit Record Review, Analysis, and Reporting](../controls/au/au-6.md) - SP 800-53 control AU-6.
- [AU-7 - Audit Record Reduction and Report Generation](../controls/au/au-7.md) - Provide and implement an audit record reduction and report generation capability that:
- [AU-8 - Time Stamps](../controls/au/au-8.md) - SP 800-53 control AU-8.
- [AU-9 - Protection of Audit Information](../controls/au/au-9.md) - SP 800-53 control AU-9.
- [AU-10 - Non-repudiation](../controls/au/au-10.md) - Provide irrefutable evidence that an individual (or process acting on behalf of an individual) has performed {{ insert: param, au-10_odp }}.
- [AU-11 - Audit Record Retention](../controls/au/au-11.md) - Retain audit records for {{ insert: param, au-11_odp }} to provide support for after-the-fact investigations of incidents and to meet regulatory and organizational information retention requirements.
- [AU-12 - Audit Record Generation](../controls/au/au-12.md) - SP 800-53 control AU-12.
- [AU-13 - Monitoring for Information Disclosure](../controls/au/au-13.md) - SP 800-53 control AU-13.
- [AU-14 - Session Audit](../controls/au/au-14.md) - SP 800-53 control AU-14.
- [AU-15 - Alternate Audit Logging Capability](../controls/au/au-15.md) - SP 800-53 control AU-15.
- [AU-16 - Cross-organizational Audit Logging](../controls/au/au-16.md) - Employ {{ insert: param, au-16_odp.01 }} for coordinating {{ insert: param, au-16_odp.02 }} among external organizations when audit information is transmitted across organizational boundaries.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
