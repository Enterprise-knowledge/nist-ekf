---
type: control
title: RA-5 - Vulnerability Monitoring and Scanning
description: SP 800-53 control RA-5.
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ra.md
  relation: part_of
  description: RA-5 - Vulnerability Monitoring and Scanning is part of its parent SP 800-53 structure.
- name: RA-5.1 - Update Tool Capability
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ra/ra-5.1.md
  relation: has_enhancement
  description: RA-5 has enhancement RA-5.1.
- name: RA-5.2 - Update Vulnerabilities to Be Scanned
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ra/ra-5.2.md
  relation: has_enhancement
  description: RA-5 has enhancement RA-5.2.
- name: RA-5.3 - Breadth and Depth of Coverage
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ra/ra-5.3.md
  relation: has_enhancement
  description: RA-5 has enhancement RA-5.3.
- name: RA-5.4 - Discoverable Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ra/ra-5.4.md
  relation: has_enhancement
  description: RA-5 has enhancement RA-5.4.
- name: RA-5.5 - Privileged Access
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ra/ra-5.5.md
  relation: has_enhancement
  description: RA-5 has enhancement RA-5.5.
- name: RA-5.6 - Automated Trend Analyses
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ra/ra-5.6.md
  relation: has_enhancement
  description: RA-5 has enhancement RA-5.6.
- name: RA-5.7 - Automated Detection and Notification of Unauthorized Components
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ra/ra-5.7.md
  relation: has_enhancement
  description: RA-5 has enhancement RA-5.7.
- name: RA-5.8 - Review Historic Audit Logs
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ra/ra-5.8.md
  relation: has_enhancement
  description: RA-5 has enhancement RA-5.8.
- name: RA-5.9 - Penetration Testing and Analyses
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ra/ra-5.9.md
  relation: has_enhancement
  description: RA-5 has enhancement RA-5.9.
- name: RA-5.10 - Correlate Scanning Information
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ra/ra-5.10.md
  relation: has_enhancement
  description: RA-5 has enhancement RA-5.10.
- name: RA-5.11 - Public Disclosure Program
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/ra/ra-5.11.md
  relation: has_enhancement
  description: RA-5 has enhancement RA-5.11.
nist_id: RA-5
sort_id: ra-05
implementation_level: organization
parameter_ids:
- ra-5_prm_1
- ra-05_odp.01
- ra-05_odp.02
- ra-05_odp.03
- ra-05_odp.04
reference_links:
- '#8df72805-2e5c-4731-a73e-81db0f0318d0'
- '#155f941a-cba9-4afd-9ca6-5d040d697ba9'
- '#a21aef46-7330-48a0-b2e1-c5bb8b2dd11d'
- '#4895b4cd-34c5-4667-bf8a-27d443c12047'
- '#122177fa-c4ed-485d-8345-3082c0fb9a06'
- '#8016d2ed-d30f-4416-9c45-0f42c7aa3232'
- '#aa5d04e0-6090-4e17-84d4-b9963d55fc2c'
- '#d2ebec9b-f868-4ee1-a2bd-0b2282aed248'
- '#4c501da5-9d79-4cb6-ba80-97260e1ce327'
- '#ca-2'
- '#ca-7'
- '#ca-8'
- '#cm-2'
- '#cm-4'
- '#cm-6'
- '#cm-8'
- '#ra-2'
- '#ra-3'
- '#sa-11'
- '#sa-15'
- '#sc-38'
- '#si-2'
- '#si-3'
- '#si-4'
- '#si-7'
- '#sr-11'
---

# Summary

SP 800-53 control RA-5.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Security categorization of information and systems guides the frequency and comprehensiveness of vulnerability monitoring (including scans). Organizations determine the required vulnerability monitoring for system components, ensuring that the potential sources of vulnerabilities—such as infrastructure components (e.g., switches, routers, guards, sensors), networked printers, scanners, and copiers—are not overlooked. The capability to readily update vulnerability monitoring tools as new vulnerabilities are discovered and announced and as new scanning methods are developed helps to ensure that new vulnerabilities are not missed by employed vulnerability monitoring tools. The vulnerability monitoring tool update process helps to ensure that potential vulnerabilities in the system are identified and addressed as quickly as possible. Vulnerability monitoring and analyses for custom software may require additional approaches, such as static analysis, dynamic analysis, binary analysis, or a hybrid of the three approaches. Organizations can use these analysis approaches in source code reviews and in a variety of tools, including web-based application scanners, static analysis tools, and binary analyzers.

Vulnerability monitoring includes scanning for patch levels; scanning for functions, ports, protocols, and services that should not be accessible to users or devices; and scanning for flow control mechanisms that are improperly configured or operating incorrectly. Vulnerability monitoring may also include continuous vulnerability monitoring tools that use instrumentation to continuously analyze components. Instrumentation-based tools may improve accuracy and may be run throughout an organization without scanning. Vulnerability monitoring tools that facilitate interoperability include tools that are Security Content Automated Protocol (SCAP)-validated. Thus, organizations consider using scanning tools that express vulnerabilities in the Common Vulnerabilities and Exposures (CVE) naming convention and that employ the Open Vulnerability Assessment Language (OVAL) to determine the presence of vulnerabilities. Sources for vulnerability information include the Common Weakness Enumeration (CWE) listing and the National Vulnerability Database (NVD). Control assessments, such as red team exercises, provide additional sources of potential vulnerabilities for which to scan. Organizations also consider using scanning tools that express vulnerability impact by the Common Vulnerability Scoring System (CVSS).

Vulnerability monitoring includes a channel and process for receiving reports of security vulnerabilities from the public at-large. Vulnerability disclosure programs can be as simple as publishing a monitored email address or web form that can receive reports, including notification authorizing good-faith research and disclosure of security vulnerabilities. Organizations generally expect that such research is happening with or without their authorization and can use public vulnerability disclosure channels to increase the likelihood that discovered vulnerabilities are reported directly to the organization for remediation.

Organizations may also employ the use of financial incentives (also known as "bug bounties" ) to further encourage external security researchers to report discovered vulnerabilities. Bug bounty programs can be tailored to the organization’s needs. Bounties can be operated indefinitely or over a defined period of time and can be offered to the general public or to a curated group. Organizations may run public and private bounties simultaneously and could choose to offer partially credentialed access to certain participants in order to evaluate security vulnerabilities from privileged vantage points.

# Parameters

- `ra-5_prm_1`
- `ra-05_odp.01`
- `ra-05_odp.02`
- `ra-05_odp.03`
- `ra-05_odp.04`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
