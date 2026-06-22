---
type: control_enhancement
title: SA-9.4 - Consistent Interests of Consumers and Providers
description: 'Take the following actions to verify that the interests of {{ insert: param, sa-09.04_odp.01 }} are
  consistent with and reflect organizational interests: {{ insert: param, sa-09.04_odp.02 }}.'
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
  description: SA-9.4 - Consistent Interests of Consumers and Providers is part of its parent SP 800-53 structure.
- name: SA-9 - External System Services
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-9.md
  relation: enhances
  description: SA-9.4 enhances base control SA-9.
nist_id: SA-9.4
sort_id: sa-09.04
implementation_level: organization
parameter_ids:
- sa-09.04_odp.01
- sa-09.04_odp.02
reference_links:
- '#sa-9'
---

# Summary

Take the following actions to verify that the interests of {{ insert: param, sa-09.04_odp.01 }} are consistent with and reflect organizational interests: {{ insert: param, sa-09.04_odp.02 }}.

# Statement

Take the following actions to verify that the interests of {{ insert: param, sa-09.04_odp.01 }} are consistent with and reflect organizational interests: {{ insert: param, sa-09.04_odp.02 }}.

# Guidance

As organizations increasingly use external service providers, it is possible that the interests of the service providers may diverge from organizational interests. In such situations, simply having the required technical, management, or operational controls in place may not be sufficient if the providers that implement and manage those controls are not operating in a manner consistent with the interests of the consuming organizations. Actions that organizations take to address such concerns include requiring background checks for selected service provider personnel; examining ownership records; employing only trustworthy service providers, such as providers with which organizations have had successful trust relationships; and conducting routine, periodic, unscheduled visits to service provider facilities.

# Parameters

- `sa-09.04_odp.01`
- `sa-09.04_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
