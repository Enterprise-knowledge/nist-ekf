---
type: control
title: SC-7 - Boundary Protection
description: SP 800-53 control SC-7.
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
- sc
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/sc.md
  relation: part_of
  description: SC-7 - Boundary Protection is part of its parent SP 800-53 structure.
- name: SC-7.1 - Physically Separated Subnetworks
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.1.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.1.
- name: SC-7.2 - Public Access
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.2.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.2.
- name: SC-7.3 - Access Points
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.3.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.3.
- name: SC-7.4 - External Telecommunications Services
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.4.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.4.
- name: SC-7.5 - Deny by Default — Allow by Exception
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.5.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.5.
- name: SC-7.6 - Response to Recognized Failures
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.6.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.6.
- name: SC-7.7 - Split Tunneling for Remote Devices
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.7.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.7.
- name: SC-7.8 - Route Traffic to Authenticated Proxy Servers
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.8.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.8.
- name: SC-7.9 - Restrict Threatening Outgoing Communications Traffic
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.9.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.9.
- name: SC-7.10 - Prevent Exfiltration
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.10.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.10.
- name: SC-7.11 - Restrict Incoming Communications Traffic
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.11.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.11.
- name: SC-7.12 - Host-based Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.12.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.12.
- name: SC-7.13 - Isolation of Security Tools, Mechanisms, and Support Components
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.13.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.13.
- name: SC-7.14 - Protect Against Unauthorized Physical Connections
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.14.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.14.
- name: SC-7.15 - Networked Privileged Accesses
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.15.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.15.
- name: SC-7.16 - Prevent Discovery of System Components
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.16.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.16.
- name: SC-7.17 - Automated Enforcement of Protocol Formats
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.17.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.17.
- name: SC-7.18 - Fail Secure
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.18.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.18.
- name: SC-7.19 - Block Communication from Non-organizationally Configured Hosts
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.19.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.19.
- name: SC-7.20 - Dynamic Isolation and Segregation
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.20.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.20.
- name: SC-7.21 - Isolation of System Components
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.21.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.21.
- name: SC-7.22 - Separate Subnets for Connecting to Different Security Domains
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.22.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.22.
- name: SC-7.23 - Disable Sender Feedback on Protocol Validation Failure
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.23.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.23.
- name: SC-7.24 - Personally Identifiable Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.24.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.24.
- name: SC-7.25 - Unclassified National Security System Connections
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.25.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.25.
- name: SC-7.26 - Classified National Security System Connections
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.26.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.26.
- name: SC-7.27 - Unclassified Non-national Security System Connections
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.27.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.27.
- name: SC-7.28 - Connections to Public Networks
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.28.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.28.
- name: SC-7.29 - Separate Subnets to Isolate Functions
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sc/sc-7.29.md
  relation: has_enhancement
  description: SC-7 has enhancement SC-7.29.
nist_id: SC-7
sort_id: sc-07
implementation_level: system
parameter_ids:
- sc-07_odp
reference_links:
- '#27847491-5ce1-4f6a-a1e4-9e483782f0ef'
- '#628d22a1-6a11-4784-bc59-5cd9497b5445'
- '#482e4c99-9dc4-41ad-bba8-0f3f0032c1f8'
- '#a7f0e897-29a3-45c4-bd88-40dfef0e034a'
- '#d4d7c760-2907-403b-8b2a-767ca5370ecd'
- '#f5edfe51-d1f2-422e-9b27-5d0e90b49c72'
- '#ac-4'
- '#ac-17'
- '#ac-18'
- '#ac-19'
- '#ac-20'
- '#au-13'
- '#ca-3'
- '#cm-2'
- '#cm-4'
- '#cm-7'
- '#cm-10'
- '#cp-8'
- '#cp-10'
- '#ir-4'
- '#ma-4'
- '#pe-3'
- '#pl-8'
- '#pm-12'
- '#sa-8'
- '#sa-17'
- '#sc-5'
- '#sc-26'
- '#sc-32'
- '#sc-35'
- '#sc-43'
---

# Summary

SP 800-53 control SC-7.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Managed interfaces include gateways, routers, firewalls, guards, network-based malicious code analysis, virtualization systems, or encrypted tunnels implemented within a security architecture. Subnetworks that are physically or logically separated from internal networks are referred to as demilitarized zones or DMZs. Restricting or prohibiting interfaces within organizational systems includes restricting external web traffic to designated web servers within managed interfaces, prohibiting external traffic that appears to be spoofing internal addresses, and prohibiting internal traffic that appears to be spoofing external addresses. [SP 800-189](#f5edfe51-d1f2-422e-9b27-5d0e90b49c72) provides additional information on source address validation techniques to prevent ingress and egress of traffic with spoofed addresses. Commercial telecommunications services are provided by network components and consolidated management systems shared by customers. These services may also include third party-provided access lines and other service elements. Such services may represent sources of increased risk despite contract security provisions. Boundary protection may be implemented as a common control for all or part of an organizational network such that the boundary to be protected is greater than a system-specific boundary (i.e., an authorization boundary).

# Parameters

- `sc-07_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
