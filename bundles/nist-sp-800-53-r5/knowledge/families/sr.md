---
type: control_family
title: SR - Supply Chain Risk Management
description: SP 800-53 control family for Supply Chain Risk Management.
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
- name: The Controls
  path: /bundles/nist-sp-800-53-r5/knowledge/sections/controls.md
  relation: part_of
  description: This family is part of the controls section.
- name: SR-1 - Policy and Procedures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-1.md
  relation: contains
  description: The family contains control SR-1.
- name: SR-2 - Supply Chain Risk Management Plan
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-2.md
  relation: contains
  description: The family contains control SR-2.
- name: SR-3 - Supply Chain Controls and Processes
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-3.md
  relation: contains
  description: The family contains control SR-3.
- name: SR-4 - Provenance
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-4.md
  relation: contains
  description: The family contains control SR-4.
- name: SR-5 - Acquisition Strategies, Tools, and Methods
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-5.md
  relation: contains
  description: The family contains control SR-5.
- name: SR-6 - Supplier Assessments and Reviews
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-6.md
  relation: contains
  description: The family contains control SR-6.
- name: SR-7 - Supply Chain Operations Security
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-7.md
  relation: contains
  description: The family contains control SR-7.
- name: SR-8 - Notification Agreements
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-8.md
  relation: contains
  description: The family contains control SR-8.
- name: SR-9 - Tamper Resistance and Detection
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-9.md
  relation: contains
  description: The family contains control SR-9.
- name: SR-10 - Inspection of Systems or Components
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-10.md
  relation: contains
  description: The family contains control SR-10.
- name: SR-11 - Component Authenticity
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-11.md
  relation: contains
  description: The family contains control SR-11.
- name: SR-12 - Component Disposal
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-12.md
  relation: contains
  description: The family contains control SR-12.
nist_id: SR
base_control_count: 12
control_enhancement_count: 15
---

# Summary

The Supply Chain Risk Management family contains 12 base controls and 15 control enhancements in the NIST OSCAL catalog.

# Controls

- [SR-1 - Policy and Procedures](../controls/sr/sr-1.md) - SP 800-53 control SR-1.
- [SR-2 - Supply Chain Risk Management Plan](../controls/sr/sr-2.md) - SP 800-53 control SR-2.
- [SR-3 - Supply Chain Controls and Processes](../controls/sr/sr-3.md) - SP 800-53 control SR-3.
- [SR-4 - Provenance](../controls/sr/sr-4.md) - Document, monitor, and maintain valid provenance of the following systems, system components, and associated data: {{ insert: param, sr-04_odp }}.
- [SR-5 - Acquisition Strategies, Tools, and Methods](../controls/sr/sr-5.md) - Employ the following acquisition strategies, contract tools, and procurement methods to protect against, identify, and mitigate supply chain risks: {{ insert: param, sr-05_odp }}.
- [SR-6 - Supplier Assessments and Reviews](../controls/sr/sr-6.md) - Assess and review the supply chain-related risks associated with suppliers or contractors and the system, system component, or system service they provide {{ insert: param, sr-06_odp }}.
- [SR-7 - Supply Chain Operations Security](../controls/sr/sr-7.md) - Employ the following Operations Security (OPSEC) controls to protect supply chain-related information for the system, system component, or system service: {{ insert: param, sr-07_odp }}.
- [SR-8 - Notification Agreements](../controls/sr/sr-8.md) - Establish agreements and procedures with entities involved in the supply chain for the system, system component, or system service for the {{ insert: param, sr-08_odp.01 }}.
- [SR-9 - Tamper Resistance and Detection](../controls/sr/sr-9.md) - Implement a tamper protection program for the system, system component, or system service.
- [SR-10 - Inspection of Systems or Components](../controls/sr/sr-10.md) - Inspect the following systems or system components {{ insert: param, sr-10_odp.02 }} to detect tampering: {{ insert: param, sr-10_odp.01 }}.
- [SR-11 - Component Authenticity](../controls/sr/sr-11.md) - SP 800-53 control SR-11.
- [SR-12 - Component Disposal](../controls/sr/sr-12.md) - Dispose of {{ insert: param, sr-12_odp.01 }} using the following techniques and methods: {{ insert: param, sr-12_odp.02 }}.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
