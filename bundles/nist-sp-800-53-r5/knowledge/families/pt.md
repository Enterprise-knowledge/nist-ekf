---
type: control_family
title: PT - Personally Identifiable Information Processing and Transparency
description: SP 800-53 control family for Personally Identifiable Information Processing and Transparency.
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
- name: The Controls
  path: /bundles/nist-sp-800-53-r5/knowledge/sections/controls.md
  relation: part_of
  description: This family is part of the controls section.
- name: PT-1 - Policy and Procedures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-1.md
  relation: contains
  description: The family contains control PT-1.
- name: PT-2 - Authority to Process Personally Identifiable Information
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-2.md
  relation: contains
  description: The family contains control PT-2.
- name: PT-3 - Personally Identifiable Information Processing Purposes
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-3.md
  relation: contains
  description: The family contains control PT-3.
- name: PT-4 - Consent
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-4.md
  relation: contains
  description: The family contains control PT-4.
- name: PT-5 - Privacy Notice
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-5.md
  relation: contains
  description: The family contains control PT-5.
- name: PT-6 - System of Records Notice
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-6.md
  relation: contains
  description: The family contains control PT-6.
- name: PT-7 - Specific Categories of Personally Identifiable Information
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-7.md
  relation: contains
  description: The family contains control PT-7.
- name: PT-8 - Computer Matching Requirements
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/pt/pt-8.md
  relation: contains
  description: The family contains control PT-8.
nist_id: PT
base_control_count: 8
control_enhancement_count: 13
---

# Summary

The Personally Identifiable Information Processing and Transparency family contains 8 base controls and 13 control enhancements in the NIST OSCAL catalog.

# Controls

- [PT-1 - Policy and Procedures](../controls/pt/pt-1.md) - SP 800-53 control PT-1.
- [PT-2 - Authority to Process Personally Identifiable Information](../controls/pt/pt-2.md) - SP 800-53 control PT-2.
- [PT-3 - Personally Identifiable Information Processing Purposes](../controls/pt/pt-3.md) - SP 800-53 control PT-3.
- [PT-4 - Consent](../controls/pt/pt-4.md) - Implement {{ insert: param, pt-04_odp }} for individuals to consent to the processing of their personally identifiable information prior to its collection that facilitate individuals’ informed decision-making.
- [PT-5 - Privacy Notice](../controls/pt/pt-5.md) - Provide notice to individuals about the processing of personally identifiable information that:
- [PT-6 - System of Records Notice](../controls/pt/pt-6.md) - For systems that process information that will be maintained in a Privacy Act system of records:
- [PT-7 - Specific Categories of Personally Identifiable Information](../controls/pt/pt-7.md) - Apply {{ insert: param, pt-07_odp }} for specific categories of personally identifiable information.
- [PT-8 - Computer Matching Requirements](../controls/pt/pt-8.md) - When a system or organization processes information for the purpose of conducting a matching program:

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
