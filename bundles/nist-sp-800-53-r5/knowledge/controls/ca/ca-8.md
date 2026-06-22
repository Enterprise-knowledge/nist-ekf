---
type: control
title: CA-8 - Penetration Testing
description: 'Conduct penetration testing {{ insert: param, ca-08_odp.01 }} on {{ insert: param, ca-08_odp.02 }}.'
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
- ca
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ca.md
  relation: part_of
  description: CA-8 - Penetration Testing is part of its parent SP 800-53 structure.
- name: CA-8.1 - Independent Penetration Testing Agent or Team
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-8.1.md
  relation: has_enhancement
  description: CA-8 has enhancement CA-8.1.
- name: CA-8.2 - Red Team Exercises
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-8.2.md
  relation: has_enhancement
  description: CA-8 has enhancement CA-8.2.
- name: CA-8.3 - Facility Penetration Testing
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ca/ca-8.3.md
  relation: has_enhancement
  description: CA-8 has enhancement CA-8.3.
nist_id: CA-8
sort_id: ca-08
implementation_level: organization
parameter_ids:
- ca-08_odp.01
- ca-08_odp.02
reference_links:
- '#ra-5'
- '#ra-10'
- '#sa-11'
- '#sr-5'
- '#sr-6'
---

# Summary

Conduct penetration testing {{ insert: param, ca-08_odp.01 }} on {{ insert: param, ca-08_odp.02 }}.

# Statement

Conduct penetration testing {{ insert: param, ca-08_odp.01 }} on {{ insert: param, ca-08_odp.02 }}.

# Guidance

Penetration testing is a specialized type of assessment conducted on systems or individual system components to identify vulnerabilities that could be exploited by adversaries. Penetration testing goes beyond automated vulnerability scanning and is conducted by agents and teams with demonstrable skills and experience that include technical expertise in network, operating system, and/or application level security. Penetration testing can be used to validate vulnerabilities or determine the degree of penetration resistance of systems to adversaries within specified constraints. Such constraints include time, resources, and skills. Penetration testing attempts to duplicate the actions of adversaries and provides a more in-depth analysis of security- and privacy-related weaknesses or deficiencies. Penetration testing is especially important when organizations are transitioning from older technologies to newer technologies (e.g., transitioning from IPv4 to IPv6 network protocols).

Organizations can use the results of vulnerability analyses to support penetration testing activities. Penetration testing can be conducted internally or externally on the hardware, software, or firmware components of a system and can exercise both physical and technical controls. A standard method for penetration testing includes a pretest analysis based on full knowledge of the system, pretest identification of potential vulnerabilities based on the pretest analysis, and testing designed to determine the exploitability of vulnerabilities. All parties agree to the rules of engagement before commencing penetration testing scenarios. Organizations correlate the rules of engagement for the penetration tests with the tools, techniques, and procedures that are anticipated to be employed by adversaries. Penetration testing may result in the exposure of information that is protected by laws or regulations, to individuals conducting the testing. Rules of engagement, contracts, or other appropriate mechanisms can be used to communicate expectations for how to protect this information. Risk assessments guide the decisions on the level of independence required for the personnel conducting penetration testing.

# Parameters

- `ca-08_odp.01`
- `ca-08_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
