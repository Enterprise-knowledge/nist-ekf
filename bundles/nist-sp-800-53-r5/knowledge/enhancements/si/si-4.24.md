---
type: control_enhancement
title: SI-4.24 - Indicators of Compromise
description: 'Discover, collect, and distribute to {{ insert: param, si-04.24_odp.02 }} , indicators of compromise
  provided by {{ insert: param, si-04.24_odp.01 }}.'
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
  description: SI-4.24 - Indicators of Compromise is part of its parent SP 800-53 structure.
- name: SI-4 - System Monitoring
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/si/si-4.md
  relation: enhances
  description: SI-4.24 enhances base control SI-4.
nist_id: SI-4.24
sort_id: si-04.24
implementation_level: system
parameter_ids:
- si-04.24_odp.01
- si-04.24_odp.02
reference_links:
- '#si-4'
- '#ac-18'
---

# Summary

Discover, collect, and distribute to {{ insert: param, si-04.24_odp.02 }} , indicators of compromise provided by {{ insert: param, si-04.24_odp.01 }}.

# Statement

Discover, collect, and distribute to {{ insert: param, si-04.24_odp.02 }} , indicators of compromise provided by {{ insert: param, si-04.24_odp.01 }}.

# Guidance

Indicators of compromise (IOC) are forensic artifacts from intrusions that are identified on organizational systems at the host or network level. IOCs provide valuable information on systems that have been compromised. IOCs can include the creation of registry key values. IOCs for network traffic include Universal Resource Locator or protocol elements that indicate malicious code command and control servers. The rapid distribution and adoption of IOCs can improve information security by reducing the time that systems and organizations are vulnerable to the same exploit or attack. Threat indicators, signatures, tactics, techniques, procedures, and other indicators of compromise may be available via government and non-government cooperatives, including the Forum of Incident Response and Security Teams, the United States Computer Emergency Readiness Team, the Defense Industrial Base Cybersecurity Information Sharing Program, and the CERT Coordination Center.

# Parameters

- `si-04.24_odp.01`
- `si-04.24_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
