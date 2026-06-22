---
type: control
title: SI-4 - System Monitoring
description: SP 800-53 control SI-4.
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
- si
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/si.md
  relation: part_of
  description: SI-4 - System Monitoring is part of its parent SP 800-53 structure.
- name: SI-4.1 - System-wide Intrusion Detection System
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.1.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.1.
- name: SI-4.2 - Automated Tools and Mechanisms for Real-time Analysis
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.2.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.2.
- name: SI-4.3 - Automated Tool and Mechanism Integration
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.3.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.3.
- name: SI-4.4 - Inbound and Outbound Communications Traffic
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.4.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.4.
- name: SI-4.5 - System-generated Alerts
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.5.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.5.
- name: SI-4.6 - Restrict Non-privileged Users
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.6.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.6.
- name: SI-4.7 - Automated Response to Suspicious Events
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.7.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.7.
- name: SI-4.8 - Protection of Monitoring Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.8.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.8.
- name: SI-4.9 - Testing of Monitoring Tools and Mechanisms
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.9.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.9.
- name: SI-4.10 - Visibility of Encrypted Communications
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.10.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.10.
- name: SI-4.11 - Analyze Communications Traffic Anomalies
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.11.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.11.
- name: SI-4.12 - Automated Organization-generated Alerts
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.12.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.12.
- name: SI-4.13 - Analyze Traffic and Event Patterns
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.13.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.13.
- name: SI-4.14 - Wireless Intrusion Detection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.14.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.14.
- name: SI-4.15 - Wireless to Wireline Communications
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.15.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.15.
- name: SI-4.16 - Correlate Monitoring Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.16.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.16.
- name: SI-4.17 - Integrated Situational Awareness
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.17.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.17.
- name: SI-4.18 - Analyze Traffic and Covert Exfiltration
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.18.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.18.
- name: SI-4.19 - Risk for Individuals
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.19.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.19.
- name: SI-4.20 - Privileged Users
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.20.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.20.
- name: SI-4.21 - Probationary Periods
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.21.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.21.
- name: SI-4.22 - Unauthorized Network Services
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.22.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.22.
- name: SI-4.23 - Host-based Devices
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.23.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.23.
- name: SI-4.24 - Indicators of Compromise
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.24.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.24.
- name: SI-4.25 - Optimize Network Traffic Analysis
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-4.25.md
  relation: has_enhancement
  description: SI-4 has enhancement SI-4.25.
nist_id: SI-4
sort_id: si-04
implementation_level: organization
parameter_ids:
- si-04_odp.01
- si-04_odp.02
- si-04_odp.03
- si-04_odp.04
- si-04_odp.05
- si-04_odp.06
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#678e3d6c-150b-4393-aec5-6e3481eb1e00'
- '#49b8aa2d-a88c-4bff-9f20-876ccb8f7dcb'
- '#3dd249b0-f57d-44ba-a03e-c3eab1b835ff'
- '#5eee45d8-3313-4fdc-8d54-1742092bbdd6'
- '#25e3e57b-dc2f-4934-af9b-050b020c6f0e'
- '#067223d8-1ec7-45c5-b21b-c848da6de8fb'
- '#ac-2'
- '#ac-3'
- '#ac-4'
- '#ac-8'
- '#ac-17'
- '#au-2'
- '#au-6'
- '#au-7'
- '#au-9'
- '#au-12'
- '#au-13'
- '#au-14'
- '#ca-7'
- '#cm-3'
- '#cm-6'
- '#cm-8'
- '#cm-11'
- '#ia-10'
- '#ir-4'
- '#ma-3'
- '#ma-4'
- '#pl-9'
- '#pm-12'
- '#ra-5'
- '#ra-10'
- '#sc-5'
- '#sc-7'
- '#sc-18'
- '#sc-26'
- '#sc-31'
- '#sc-35'
- '#sc-36'
- '#sc-37'
- '#sc-43'
- '#si-3'
- '#si-6'
- '#si-7'
- '#sr-9'
- '#sr-10'
---

# Summary

SP 800-53 control SI-4.

# Statement

No statement text was present in the OSCAL record.

# Guidance

System monitoring includes external and internal monitoring. External monitoring includes the observation of events occurring at external interfaces to the system. Internal monitoring includes the observation of events occurring within the system. Organizations monitor systems by observing audit activities in real time or by observing other system aspects such as access patterns, characteristics of access, and other actions. The monitoring objectives guide and inform the determination of the events. System monitoring capabilities are achieved through a variety of tools and techniques, including intrusion detection and prevention systems, malicious code protection software, scanning tools, audit record monitoring software, and network monitoring software.

Depending on the security architecture, the distribution and configuration of monitoring devices may impact throughput at key internal and external boundaries as well as at other locations across a network due to the introduction of network throughput latency. If throughput management is needed, such devices are strategically located and deployed as part of an established organization-wide security architecture. Strategic locations for monitoring devices include selected perimeter locations and near key servers and server farms that support critical applications. Monitoring devices are typically employed at the managed interfaces associated with controls [SC-7](#sc-7) and [AC-17](#ac-17) . The information collected is a function of the organizational monitoring objectives and the capability of systems to support such objectives. Specific types of transactions of interest include Hypertext Transfer Protocol (HTTP) traffic that bypasses HTTP proxies. System monitoring is an integral part of organizational continuous monitoring and incident response programs, and output from system monitoring serves as input to those programs. System monitoring requirements, including the need for specific types of system monitoring, may be referenced in other controls (e.g., [AC-2g](#ac-2_smt.g), [AC-2(7)](#ac-2.7), [AC-2(12)(a)](#ac-2.12_smt.a), [AC-17(1)](#ac-17.1), [AU-13](#au-13), [AU-13(1)](#au-13.1), [AU-13(2)](#au-13.2), [CM-3f](#cm-3_smt.f), [CM-6d](#cm-6_smt.d), [MA-3a](#ma-3_smt.a), [MA-4a](#ma-4_smt.a), [SC-5(3)(b)](#sc-5.3_smt.b), [SC-7a](#sc-7_smt.a), [SC-7(24)(b)](#sc-7.24_smt.b), [SC-18b](#sc-18_smt.b), [SC-43b](#sc-43_smt.b) ). Adjustments to levels of system monitoring are based on law enforcement information, intelligence information, or other sources of information. The legality of system monitoring activities is based on applicable laws, executive orders, directives, regulations, policies, standards, and guidelines.

# Parameters

- `si-04_odp.01`
- `si-04_odp.02`
- `si-04_odp.03`
- `si-04_odp.04`
- `si-04_odp.05`
- `si-04_odp.06`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
