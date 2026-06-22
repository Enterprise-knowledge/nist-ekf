---
type: control
title: SI-3 - Malicious Code Protection
description: SP 800-53 control SI-3.
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
  description: SI-3 - Malicious Code Protection is part of its parent SP 800-53 structure.
- name: SI-3.1 - Central Management
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-3.1.md
  relation: has_enhancement
  description: SI-3 has enhancement SI-3.1.
- name: SI-3.2 - Automatic Updates
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-3.2.md
  relation: has_enhancement
  description: SI-3 has enhancement SI-3.2.
- name: SI-3.3 - Non-privileged Users
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-3.3.md
  relation: has_enhancement
  description: SI-3 has enhancement SI-3.3.
- name: SI-3.4 - Updates Only by Privileged Users
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-3.4.md
  relation: has_enhancement
  description: SI-3 has enhancement SI-3.4.
- name: SI-3.5 - Portable Storage Devices
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-3.5.md
  relation: has_enhancement
  description: SI-3 has enhancement SI-3.5.
- name: SI-3.6 - Testing and Verification
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-3.6.md
  relation: has_enhancement
  description: SI-3 has enhancement SI-3.6.
- name: SI-3.7 - Nonsignature-based Detection
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-3.7.md
  relation: has_enhancement
  description: SI-3 has enhancement SI-3.7.
- name: SI-3.8 - Detect Unauthorized Commands
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-3.8.md
  relation: has_enhancement
  description: SI-3 has enhancement SI-3.8.
- name: SI-3.9 - Authenticate Remote Commands
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-3.9.md
  relation: has_enhancement
  description: SI-3 has enhancement SI-3.9.
- name: SI-3.10 - Malicious Code Analysis
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-3.10.md
  relation: has_enhancement
  description: SI-3 has enhancement SI-3.10.
nist_id: SI-3
sort_id: si-03
implementation_level: organization
parameter_ids:
- si-03_odp.01
- si-03_odp.02
- si-03_odp.03
- si-03_odp.04
- si-03_odp.05
- si-03_odp.06
reference_links:
- '#3dd249b0-f57d-44ba-a03e-c3eab1b835ff'
- '#88660532-2dcf-442e-845c-03340ce48999'
- '#1c71b420-2bd9-4e52-9fc8-390f58b85b59'
- '#ac-4'
- '#ac-19'
- '#cm-3'
- '#cm-8'
- '#ir-4'
- '#ma-3'
- '#ma-4'
- '#pl-9'
- '#ra-5'
- '#sc-7'
- '#sc-23'
- '#sc-26'
- '#sc-28'
- '#sc-44'
- '#si-2'
- '#si-4'
- '#si-7'
- '#si-8'
- '#si-15'
---

# Summary

SP 800-53 control SI-3.

# Statement

No statement text was present in the OSCAL record.

# Guidance

System entry and exit points include firewalls, remote access servers, workstations, electronic mail servers, web servers, proxy servers, notebook computers, and mobile devices. Malicious code includes viruses, worms, Trojan horses, and spyware. Malicious code can also be encoded in various formats contained within compressed or hidden files or hidden in files using techniques such as steganography. Malicious code can be inserted into systems in a variety of ways, including by electronic mail, the world-wide web, and portable storage devices. Malicious code insertions occur through the exploitation of system vulnerabilities. A variety of technologies and methods exist to limit or eliminate the effects of malicious code.

Malicious code protection mechanisms include both signature- and nonsignature-based technologies. Nonsignature-based detection mechanisms include artificial intelligence techniques that use heuristics to detect, analyze, and describe the characteristics or behavior of malicious code and to provide controls against such code for which signatures do not yet exist or for which existing signatures may not be effective. Malicious code for which active signatures do not yet exist or may be ineffective includes polymorphic malicious code (i.e., code that changes signatures when it replicates). Nonsignature-based mechanisms also include reputation-based technologies. In addition to the above technologies, pervasive configuration management, comprehensive software integrity controls, and anti-exploitation software may be effective in preventing the execution of unauthorized code. Malicious code may be present in commercial off-the-shelf software as well as custom-built software and could include logic bombs, backdoors, and other types of attacks that could affect organizational mission and business functions.

In situations where malicious code cannot be detected by detection methods or technologies, organizations rely on other types of controls, including secure coding practices, configuration management and control, trusted procurement processes, and monitoring practices to ensure that software does not perform functions other than the functions intended. Organizations may determine that, in response to the detection of malicious code, different actions may be warranted. For example, organizations can define actions in response to malicious code detection during periodic scans, the detection of malicious downloads, or the detection of maliciousness when attempting to open or execute files.

# Parameters

- `si-03_odp.01`
- `si-03_odp.02`
- `si-03_odp.03`
- `si-03_odp.04`
- `si-03_odp.05`
- `si-03_odp.06`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
