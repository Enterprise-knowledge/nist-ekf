---
type: control
title: SC-6 - Resource Availability
description: 'Protect the availability of resources by allocating {{ insert: param, sc-06_odp.01 }} by {{ insert:
  param, sc-06_odp.02 }}.'
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
  description: SC-6 - Resource Availability is part of its parent SP 800-53 structure.
nist_id: SC-6
sort_id: sc-06
implementation_level: system
parameter_ids:
- sc-06_odp.01
- sc-06_odp.02
- sc-06_odp.03
reference_links:
- '#047b041a-b4b0-4537-ab2d-2b36283eeda0'
- '#4f42ee6e-86cc-403b-a51f-76c2b4f81b54'
- '#sc-5'
---

# Summary

Protect the availability of resources by allocating {{ insert: param, sc-06_odp.01 }} by {{ insert: param, sc-06_odp.02 }}.

# Statement

Protect the availability of resources by allocating {{ insert: param, sc-06_odp.01 }} by {{ insert: param, sc-06_odp.02 }}.

# Guidance

Priority protection prevents lower-priority processes from delaying or interfering with the system that services higher-priority processes. Quotas prevent users or processes from obtaining more than predetermined amounts of resources.

# Parameters

- `sc-06_odp.01`
- `sc-06_odp.02`
- `sc-06_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
