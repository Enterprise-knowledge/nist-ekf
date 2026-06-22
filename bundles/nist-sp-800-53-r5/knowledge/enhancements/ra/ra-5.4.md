---
type: control_enhancement
title: RA-5.4 - Discoverable Information
description: 'Determine information about the system that is discoverable and take {{ insert: param, ra-05.04_odp
  }}.'
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-5.md
  relation: part_of
  description: RA-5.4 - Discoverable Information is part of its parent SP 800-53 structure.
- name: RA-5 - Vulnerability Monitoring and Scanning
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-5.md
  relation: enhances
  description: RA-5.4 enhances base control RA-5.
nist_id: RA-5.4
sort_id: ra-05.04
implementation_level: organization
parameter_ids:
- ra-05.04_odp
reference_links:
- '#ra-5'
- '#au-13'
- '#sc-26'
---

# Summary

Determine information about the system that is discoverable and take {{ insert: param, ra-05.04_odp }}.

# Statement

Determine information about the system that is discoverable and take {{ insert: param, ra-05.04_odp }}.

# Guidance

Discoverable information includes information that adversaries could obtain without compromising or breaching the system, such as by collecting information that the system is exposing or by conducting extensive web searches. Corrective actions include notifying appropriate organizational personnel, removing designated information, or changing the system to make the designated information less relevant or attractive to adversaries. This enhancement excludes intentionally discoverable information that may be part of a decoy capability (e.g., honeypots, honeynets, or deception nets) deployed by the organization.

# Parameters

- `ra-05.04_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
