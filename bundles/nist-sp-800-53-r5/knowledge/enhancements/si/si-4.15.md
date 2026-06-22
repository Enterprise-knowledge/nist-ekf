---
type: control_enhancement
title: SI-4.15 - Wireless to Wireline Communications
description: Employ an intrusion detection system to monitor wireless communications traffic as the traffic passes
  from wireless to wireline networks.
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- control-enhancement
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-4.md
  relation: part_of
  description: SI-4.15 - Wireless to Wireline Communications is part of its parent SP 800-53 structure.
- name: SI-4 - System Monitoring
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-4.md
  relation: enhances
  description: SI-4.15 enhances base control SI-4.
nist_id: SI-4.15
sort_id: si-04.15
implementation_level: system
parameter_ids: []
reference_links:
- '#si-4'
- '#ac-18'
---

# Summary

Employ an intrusion detection system to monitor wireless communications traffic as the traffic passes from wireless to wireline networks.

# Statement

Employ an intrusion detection system to monitor wireless communications traffic as the traffic passes from wireless to wireline networks.

# Guidance

Wireless networks are inherently less secure than wired networks. For example, wireless networks are more susceptible to eavesdroppers or traffic analysis than wireline networks. When wireless to wireline communications exist, the wireless network could become a port of entry into the wired network. Given the greater facility of unauthorized network access via wireless access points compared to unauthorized wired network access from within the physical boundaries of the system, additional monitoring of transitioning traffic between wireless and wired networks may be necessary to detect malicious activities. Employing intrusion detection systems to monitor wireless communications traffic helps to ensure that the traffic does not contain malicious code prior to transitioning to the wireline network.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
