---
type: control_enhancement
title: SC-5.3 - Detection and Monitoring
description: SP 800-53 control SC-5.3.
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-5.md
  relation: part_of
  description: SC-5.3 - Detection and Monitoring is part of its parent SP 800-53 structure.
- name: SC-5 - Denial-of-service Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sc/sc-5.md
  relation: enhances
  description: SC-5.3 enhances base control SC-5.
nist_id: SC-5.3
sort_id: sc-05.03
implementation_level: system
parameter_ids:
- sc-05.03_odp.01
- sc-05.03_odp.02
reference_links:
- '#sc-5'
- '#ca-7'
- '#si-4'
---

# Summary

SP 800-53 control SC-5.3.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Organizations consider the utilization and capacity of system resources when managing risk associated with a denial of service due to malicious attacks. Denial-of-service attacks can originate from external or internal sources. System resources that are sensitive to denial of service include physical disk storage, memory, and CPU cycles. Techniques used to prevent denial-of-service attacks related to storage utilization and capacity include instituting disk quotas, configuring systems to automatically alert administrators when specific storage capacity thresholds are reached, using file compression technologies to maximize available storage space, and imposing separate partitions for system and user data.

# Parameters

- `sc-05.03_odp.01`
- `sc-05.03_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
