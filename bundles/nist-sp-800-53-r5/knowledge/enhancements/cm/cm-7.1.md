---
type: control_enhancement
title: CM-7.1 - Periodic Review
description: SP 800-53 control CM-7.1.
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
- cm
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-7.md
  relation: part_of
  description: CM-7.1 - Periodic Review is part of its parent SP 800-53 structure.
- name: CM-7 - Least Functionality
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-7.md
  relation: enhances
  description: CM-7.1 enhances base control CM-7.
nist_id: CM-7.1
sort_id: cm-07.01
implementation_level: organization
parameter_ids:
- cm-7.1_prm_2
- cm-07.01_odp.01
- cm-07.01_odp.02
- cm-07.01_odp.03
- cm-07.01_odp.04
- cm-07.01_odp.05
- cm-07.01_odp.06
reference_links:
- '#cm-7'
- '#ac-18'
---

# Summary

SP 800-53 control CM-7.1.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Organizations review functions, ports, protocols, and services provided by systems or system components to determine the functions and services that are candidates for elimination. Such reviews are especially important during transition periods from older technologies to newer technologies (e.g., transition from IPv4 to IPv6). These technology transitions may require implementing the older and newer technologies simultaneously during the transition period and returning to minimum essential functions, ports, protocols, and services at the earliest opportunity. Organizations can either decide the relative security of the function, port, protocol, and/or service or base the security decision on the assessment of other entities. Unsecure protocols include Bluetooth, FTP, and peer-to-peer networking.

# Parameters

- `cm-7.1_prm_2`
- `cm-07.01_odp.01`
- `cm-07.01_odp.02`
- `cm-07.01_odp.03`
- `cm-07.01_odp.04`
- `cm-07.01_odp.05`
- `cm-07.01_odp.06`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
