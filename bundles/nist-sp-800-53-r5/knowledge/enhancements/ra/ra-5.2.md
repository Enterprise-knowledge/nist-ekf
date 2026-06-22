---
type: control_enhancement
title: RA-5.2 - Update Vulnerabilities to Be Scanned
description: 'Update the system vulnerabilities to be scanned {{ insert: param, ra-05.02_odp.01 }}.'
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
  description: RA-5.2 - Update Vulnerabilities to Be Scanned is part of its parent SP 800-53 structure.
- name: RA-5 - Vulnerability Monitoring and Scanning
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-5.md
  relation: enhances
  description: RA-5.2 enhances base control RA-5.
nist_id: RA-5.2
sort_id: ra-05.02
implementation_level: organization
parameter_ids:
- ra-05.02_odp.01
- ra-05.02_odp.02
reference_links:
- '#ra-5'
- '#si-5'
---

# Summary

Update the system vulnerabilities to be scanned {{ insert: param, ra-05.02_odp.01 }}.

# Statement

Update the system vulnerabilities to be scanned {{ insert: param, ra-05.02_odp.01 }}.

# Guidance

Due to the complexity of modern software, systems, and other factors, new vulnerabilities are discovered on a regular basis. It is important that newly discovered vulnerabilities are added to the list of vulnerabilities to be scanned to ensure that the organization can take steps to mitigate those vulnerabilities in a timely manner.

# Parameters

- `ra-05.02_odp.01`
- `ra-05.02_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
