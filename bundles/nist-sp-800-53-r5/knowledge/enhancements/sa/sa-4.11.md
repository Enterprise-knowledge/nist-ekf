---
type: control_enhancement
title: SA-4.11 - System of Records
description: 'Include {{ insert: param, sa-04.11_odp }} in the acquisition contract for the operation of a system
  of records on behalf of an organization to accomplish an organizational mission or function.'
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
- sa
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-4.md
  relation: part_of
  description: SA-4.11 - System of Records is part of its parent SP 800-53 structure.
- name: SA-4 - Acquisition Process
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-4.md
  relation: enhances
  description: SA-4.11 enhances base control SA-4.
nist_id: SA-4.11
sort_id: sa-04.11
implementation_level: organization
parameter_ids:
- sa-04.11_odp
reference_links:
- '#sa-4'
- '#pt-6'
---

# Summary

Include {{ insert: param, sa-04.11_odp }} in the acquisition contract for the operation of a system of records on behalf of an organization to accomplish an organizational mission or function.

# Statement

Include {{ insert: param, sa-04.11_odp }} in the acquisition contract for the operation of a system of records on behalf of an organization to accomplish an organizational mission or function.

# Guidance

When, by contract, an organization provides for the operation of a system of records to accomplish an organizational mission or function, the organization, consistent with its authority, causes the requirements of the [PRIVACT](#18e71fec-c6fd-475a-925a-5d8495cf8455) to be applied to the system of records.

# Parameters

- `sa-04.11_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
