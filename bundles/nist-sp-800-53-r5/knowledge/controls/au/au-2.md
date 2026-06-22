---
type: control
title: AU-2 - Event Logging
description: SP 800-53 control AU-2.
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
  description: AU-2 - Event Logging is part of its parent SP 800-53 structure.
- name: AU-2.1 - Compilation of Audit Records from Multiple Sources
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-2.1.md
  relation: has_enhancement
  description: AU-2 has enhancement AU-2.1.
- name: AU-2.2 - Selection of Audit Events by Component
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-2.2.md
  relation: has_enhancement
  description: AU-2 has enhancement AU-2.2.
- name: AU-2.3 - Reviews and Updates
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-2.3.md
  relation: has_enhancement
  description: AU-2 has enhancement AU-2.3.
- name: AU-2.4 - Privileged Functions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/au/au-2.4.md
  relation: has_enhancement
  description: AU-2 has enhancement AU-2.4.
nist_id: AU-2
sort_id: au-02
implementation_level: organization
parameter_ids:
- au-2_prm_2
- au-02_odp.01
- au-02_odp.02
- au-02_odp.03
- au-02_odp.04
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#5eee45d8-3313-4fdc-8d54-1742092bbdd6'
- '#ac-2'
- '#ac-3'
- '#ac-6'
- '#ac-7'
- '#ac-8'
- '#ac-16'
- '#ac-17'
- '#au-3'
- '#au-4'
- '#au-5'
- '#au-6'
- '#au-7'
- '#au-11'
- '#au-12'
- '#cm-3'
- '#cm-5'
- '#cm-6'
- '#cm-13'
- '#ia-3'
- '#ma-4'
- '#mp-4'
- '#pe-3'
- '#pm-21'
- '#pt-2'
- '#pt-7'
- '#ra-8'
- '#sa-8'
- '#sc-7'
- '#sc-18'
- '#si-3'
- '#si-4'
- '#si-7'
- '#si-10'
- '#si-11'
---

# Summary

SP 800-53 control AU-2.

# Statement

No statement text was present in the OSCAL record.

# Guidance

An event is an observable occurrence in a system. The types of events that require logging are those events that are significant and relevant to the security of systems and the privacy of individuals. Event logging also supports specific monitoring and auditing needs. Event types include password changes, failed logons or failed accesses related to systems, security or privacy attribute changes, administrative privilege usage, PIV credential usage, data action changes, query parameters, or external credential usage. In determining the set of event types that require logging, organizations consider the monitoring and auditing appropriate for each of the controls to be implemented. For completeness, event logging includes all protocols that are operational and supported by the system.

To balance monitoring and auditing requirements with other system needs, event logging requires identifying the subset of event types that are logged at a given point in time. For example, organizations may determine that systems need the capability to log every file access successful and unsuccessful, but not activate that capability except for specific circumstances due to the potential burden on system performance. The types of events that organizations desire to be logged may change. Reviewing and updating the set of logged events is necessary to help ensure that the events remain relevant and continue to support the needs of the organization. Organizations consider how the types of logging events can reveal information about individuals that may give rise to privacy risk and how best to mitigate such risks. For example, there is the potential to reveal personally identifiable information in the audit trail, especially if the logging event is based on patterns or time of usage.

Event logging requirements, including the need to log specific event types, may be referenced in other controls and control enhancements. These include [AC-2(4)](#ac-2.4), [AC-3(10)](#ac-3.10), [AC-6(9)](#ac-6.9), [AC-17(1)](#ac-17.1), [CM-3f](#cm-3_smt.f), [CM-5(1)](#cm-5.1), [IA-3(3)(b)](#ia-3.3_smt.b), [MA-4(1)](#ma-4.1), [MP-4(2)](#mp-4.2), [PE-3](#pe-3), [PM-21](#pm-21), [PT-7](#pt-7), [RA-8](#ra-8), [SC-7(9)](#sc-7.9), [SC-7(15)](#sc-7.15), [SI-3(8)](#si-3.8), [SI-4(22)](#si-4.22), [SI-7(8)](#si-7.8) , and [SI-10(1)](#si-10.1) . Organizations include event types that are required by applicable laws, executive orders, directives, policies, regulations, standards, and guidelines. Audit records can be generated at various levels, including at the packet level as information traverses the network. Selecting the appropriate level of event logging is an important part of a monitoring and auditing capability and can identify the root causes of problems. When defining event types, organizations consider the logging necessary to cover related event types, such as the steps in distributed, transaction-based processes and the actions that occur in service-oriented architectures.

# Parameters

- `au-2_prm_2`
- `au-02_odp.01`
- `au-02_odp.02`
- `au-02_odp.03`
- `au-02_odp.04`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
