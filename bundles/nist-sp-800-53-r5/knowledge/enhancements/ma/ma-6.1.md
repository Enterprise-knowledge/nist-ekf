---
type: control_enhancement
title: MA-6.1 - Preventive Maintenance
description: 'Perform preventive maintenance on {{ insert: param, ma-06.01_odp.01 }} at {{ insert: param, ma-06.01_odp.02
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
- ma
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-6.md
  relation: part_of
  description: MA-6.1 - Preventive Maintenance is part of its parent SP 800-53 structure.
- name: MA-6 - Timely Maintenance
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ma/ma-6.md
  relation: enhances
  description: MA-6.1 enhances base control MA-6.
nist_id: MA-6.1
sort_id: ma-06.01
implementation_level: organization
parameter_ids:
- ma-06.01_odp.01
- ma-06.01_odp.02
reference_links:
- '#ma-6'
---

# Summary

Perform preventive maintenance on {{ insert: param, ma-06.01_odp.01 }} at {{ insert: param, ma-06.01_odp.02 }}.

# Statement

Perform preventive maintenance on {{ insert: param, ma-06.01_odp.01 }} at {{ insert: param, ma-06.01_odp.02 }}.

# Guidance

Preventive maintenance includes proactive care and the servicing of system components to maintain organizational equipment and facilities in satisfactory operating condition. Such maintenance provides for the systematic inspection, tests, measurements, adjustments, parts replacement, detection, and correction of incipient failures either before they occur or before they develop into major defects. The primary goal of preventive maintenance is to avoid or mitigate the consequences of equipment failures. Preventive maintenance is designed to preserve and restore equipment reliability by replacing worn components before they fail. Methods of determining what preventive (or other) failure management policies to apply include original equipment manufacturer recommendations; statistical failure records; expert opinion; maintenance that has already been conducted on similar equipment; requirements of codes, laws, or regulations within a jurisdiction; or measured values and performance indications.

# Parameters

- `ma-06.01_odp.01`
- `ma-06.01_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
