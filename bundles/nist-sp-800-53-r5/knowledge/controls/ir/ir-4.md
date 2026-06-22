---
type: control
title: IR-4 - Incident Handling
description: SP 800-53 control IR-4.
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
- ir
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ir.md
  relation: part_of
  description: IR-4 - Incident Handling is part of its parent SP 800-53 structure.
- name: IR-4.1 - Automated Incident Handling Processes
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-4.1.md
  relation: has_enhancement
  description: IR-4 has enhancement IR-4.1.
- name: IR-4.2 - Dynamic Reconfiguration
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-4.2.md
  relation: has_enhancement
  description: IR-4 has enhancement IR-4.2.
- name: IR-4.3 - Continuity of Operations
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-4.3.md
  relation: has_enhancement
  description: IR-4 has enhancement IR-4.3.
- name: IR-4.4 - Information Correlation
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-4.4.md
  relation: has_enhancement
  description: IR-4 has enhancement IR-4.4.
- name: IR-4.5 - Automatic Disabling of System
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-4.5.md
  relation: has_enhancement
  description: IR-4 has enhancement IR-4.5.
- name: IR-4.6 - Insider Threats
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-4.6.md
  relation: has_enhancement
  description: IR-4 has enhancement IR-4.6.
- name: IR-4.7 - Insider Threats — Intra-organization Coordination
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-4.7.md
  relation: has_enhancement
  description: IR-4 has enhancement IR-4.7.
- name: IR-4.8 - Correlation with External Organizations
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-4.8.md
  relation: has_enhancement
  description: IR-4 has enhancement IR-4.8.
- name: IR-4.9 - Dynamic Response Capability
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-4.9.md
  relation: has_enhancement
  description: IR-4 has enhancement IR-4.9.
- name: IR-4.10 - Supply Chain Coordination
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-4.10.md
  relation: has_enhancement
  description: IR-4 has enhancement IR-4.10.
- name: IR-4.11 - Integrated Incident Response Team
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-4.11.md
  relation: has_enhancement
  description: IR-4 has enhancement IR-4.11.
- name: IR-4.12 - Malicious Code and Forensic Analysis
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-4.12.md
  relation: has_enhancement
  description: IR-4 has enhancement IR-4.12.
- name: IR-4.13 - Behavior Analysis
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-4.13.md
  relation: has_enhancement
  description: IR-4 has enhancement IR-4.13.
- name: IR-4.14 - Security Operations Center
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-4.14.md
  relation: has_enhancement
  description: IR-4 has enhancement IR-4.14.
- name: IR-4.15 - Public Relations and Reputation Repair
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ir/ir-4.15.md
  relation: has_enhancement
  description: IR-4 has enhancement IR-4.15.
nist_id: IR-4
sort_id: ir-04
implementation_level: organization
parameter_ids: []
reference_links:
- '#4ff10ed3-d8fe-4246-99e3-443045e27482'
- '#0f963c17-ab5a-432a-a867-91eac550309b'
- '#5f4705ac-8d17-438c-b23a-ac7f12362ae4'
- '#49b8aa2d-a88c-4bff-9f20-876ccb8f7dcb'
- '#cfdb1858-c473-46b3-89f9-a700308d0be2'
- '#10cf2fad-a216-41f9-bb1a-531b7e3119e3'
- '#9ef4b43c-42a4-4316-87dc-ffaf528bc05c'
- '#61ccf0f4-d3e7-42db-9796-ce6cb1c85989'
- '#31ae65ab-3f26-46b7-9d64-f25a4dac5778'
- '#2be7b163-e50a-435c-8906-f1162f2a457a'
- '#ac-19'
- '#au-6'
- '#au-7'
- '#cm-6'
- '#cp-2'
- '#cp-3'
- '#cp-4'
- '#ir-2'
- '#ir-3'
- '#ir-5'
- '#ir-6'
- '#ir-8'
- '#pe-6'
- '#pl-2'
- '#pm-12'
- '#sa-8'
- '#sc-5'
- '#sc-7'
- '#si-3'
- '#si-4'
- '#si-7'
---

# Summary

SP 800-53 control IR-4.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Organizations recognize that incident response capabilities are dependent on the capabilities of organizational systems and the mission and business processes being supported by those systems. Organizations consider incident response as part of the definition, design, and development of mission and business processes and systems. Incident-related information can be obtained from a variety of sources, including audit monitoring, physical access monitoring, and network monitoring; user or administrator reports; and reported supply chain events. An effective incident handling capability includes coordination among many organizational entities (e.g., mission or business owners, system owners, authorizing officials, human resources offices, physical security offices, personnel security offices, legal departments, risk executive [function], operations personnel, procurement offices). Suspected security incidents include the receipt of suspicious email communications that can contain malicious code. Suspected supply chain incidents include the insertion of counterfeit hardware or malicious code into organizational systems or system components. For federal agencies, an incident that involves personally identifiable information is considered a breach. A breach results in unauthorized disclosure, the loss of control, unauthorized acquisition, compromise, or a similar occurrence where a person other than an authorized user accesses or potentially accesses personally identifiable information or an authorized user accesses or potentially accesses such information for other than authorized purposes.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
