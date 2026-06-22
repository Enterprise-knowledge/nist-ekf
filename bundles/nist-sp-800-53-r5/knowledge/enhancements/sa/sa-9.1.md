---
type: control_enhancement
title: SA-9.1 - Risk Assessments and Organizational Approvals
description: SP 800-53 control SA-9.1.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-9.md
  relation: part_of
  description: SA-9.1 - Risk Assessments and Organizational Approvals is part of its parent SP 800-53 structure.
- name: SA-9 - External System Services
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-9.md
  relation: enhances
  description: SA-9.1 enhances base control SA-9.
nist_id: SA-9.1
sort_id: sa-09.01
implementation_level: organization
parameter_ids:
- sa-09.01_odp
reference_links:
- '#sa-9'
- '#ca-6'
- '#ra-3'
- '#ra-8'
---

# Summary

SP 800-53 control SA-9.1.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Information security services include the operation of security devices, such as firewalls or key management services as well as incident monitoring, analysis, and response. Risks assessed can include system, mission or business, security, privacy, or supply chain risks.

# Parameters

- `sa-09.01_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
