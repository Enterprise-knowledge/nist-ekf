---
type: control
title: AU-6 - Audit Record Review, Analysis, and Reporting
description: SP 800-53 control AU-6.
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/au.md
  relation: part_of
  description: AU-6 - Audit Record Review, Analysis, and Reporting is part of its parent SP 800-53 structure.
- name: AU-6.1 - Automated Process Integration
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-6.1.md
  relation: has_enhancement
  description: AU-6 has enhancement AU-6.1.
- name: AU-6.2 - Automated Security Alerts
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-6.2.md
  relation: has_enhancement
  description: AU-6 has enhancement AU-6.2.
- name: AU-6.3 - Correlate Audit Record Repositories
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-6.3.md
  relation: has_enhancement
  description: AU-6 has enhancement AU-6.3.
- name: AU-6.4 - Central Review and Analysis
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-6.4.md
  relation: has_enhancement
  description: AU-6 has enhancement AU-6.4.
- name: AU-6.5 - Integrated Analysis of Audit Records
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-6.5.md
  relation: has_enhancement
  description: AU-6 has enhancement AU-6.5.
- name: AU-6.6 - Correlation with Physical Monitoring
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-6.6.md
  relation: has_enhancement
  description: AU-6 has enhancement AU-6.6.
- name: AU-6.7 - Permitted Actions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-6.7.md
  relation: has_enhancement
  description: AU-6 has enhancement AU-6.7.
- name: AU-6.8 - Full Text Analysis of Privileged Commands
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-6.8.md
  relation: has_enhancement
  description: AU-6 has enhancement AU-6.8.
- name: AU-6.9 - Correlation with Information from Nontechnical Sources
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-6.9.md
  relation: has_enhancement
  description: AU-6 has enhancement AU-6.9.
- name: AU-6.10 - Audit Level Adjustment
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-6.10.md
  relation: has_enhancement
  description: AU-6 has enhancement AU-6.10.
nist_id: AU-6
sort_id: au-06
implementation_level: organization
parameter_ids:
- au-06_odp.01
- au-06_odp.02
- au-06_odp.03
reference_links:
- '#cfdb1858-c473-46b3-89f9-a700308d0be2'
- '#10cf2fad-a216-41f9-bb1a-531b7e3119e3'
- '#ac-2'
- '#ac-3'
- '#ac-5'
- '#ac-6'
- '#ac-7'
- '#ac-17'
- '#au-7'
- '#au-16'
- '#ca-2'
- '#ca-7'
- '#cm-2'
- '#cm-5'
- '#cm-6'
- '#cm-10'
- '#cm-11'
- '#ia-2'
- '#ia-3'
- '#ia-5'
- '#ia-8'
- '#ir-5'
- '#ma-4'
- '#mp-4'
- '#pe-3'
- '#pe-6'
- '#ra-5'
- '#sa-8'
- '#sc-7'
- '#si-3'
- '#si-4'
- '#si-7'
---

# Summary

SP 800-53 control AU-6.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Audit record review, analysis, and reporting covers information security- and privacy-related logging performed by organizations, including logging that results from the monitoring of account usage, remote access, wireless connectivity, mobile device connection, configuration settings, system component inventory, use of maintenance tools and non-local maintenance, physical access, temperature and humidity, equipment delivery and removal, communications at system interfaces, and use of mobile code or Voice over Internet Protocol (VoIP). Findings can be reported to organizational entities that include the incident response team, help desk, and security or privacy offices. If organizations are prohibited from reviewing and analyzing audit records or unable to conduct such activities, the review or analysis may be carried out by other organizations granted such authority. The frequency, scope, and/or depth of the audit record review, analysis, and reporting may be adjusted to meet organizational needs based on new information received.

# Parameters

- `au-06_odp.01`
- `au-06_odp.02`
- `au-06_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
