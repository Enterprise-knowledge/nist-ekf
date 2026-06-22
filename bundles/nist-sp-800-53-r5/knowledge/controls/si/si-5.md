---
type: control
title: SI-5 - Security Alerts, Advisories, and Directives
description: SP 800-53 control SI-5.
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
  description: SI-5 - Security Alerts, Advisories, and Directives is part of its parent SP 800-53 structure.
- name: SI-5.1 - Automated Alerts and Advisories
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/si/si-5.1.md
  relation: has_enhancement
  description: SI-5 has enhancement SI-5.1.
nist_id: SI-5
sort_id: si-05
implementation_level: organization
parameter_ids:
- si-05_odp.01
- si-05_odp.02
- si-05_odp.03
- si-05_odp.04
- si-05_odp.05
reference_links:
- '#155f941a-cba9-4afd-9ca6-5d040d697ba9'
- '#pm-15'
- '#ra-5'
- '#si-2'
---

# Summary

SP 800-53 control SI-5.

# Statement

No statement text was present in the OSCAL record.

# Guidance

The Cybersecurity and Infrastructure Security Agency (CISA) generates security alerts and advisories to maintain situational awareness throughout the Federal Government. Security directives are issued by OMB or other designated organizations with the responsibility and authority to issue such directives. Compliance with security directives is essential due to the critical nature of many of these directives and the potential (immediate) adverse effects on organizational operations and assets, individuals, other organizations, and the Nation should the directives not be implemented in a timely manner. External organizations include supply chain partners, external mission or business partners, external service providers, and other peer or supporting organizations.

# Parameters

- `si-05_odp.01`
- `si-05_odp.02`
- `si-05_odp.03`
- `si-05_odp.04`
- `si-05_odp.05`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
