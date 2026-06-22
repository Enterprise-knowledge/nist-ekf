---
type: control_enhancement
title: SA-9.3 - Establish and Maintain Trust Relationship with Providers
description: 'Establish, document, and maintain trust relationships with external service providers based on the
  following requirements, properties, factors, or conditions: {{ insert: param, sa-9.3_prm_1 }}.'
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
  description: SA-9.3 - Establish and Maintain Trust Relationship with Providers is part of its parent SP 800-53
    structure.
- name: SA-9 - External System Services
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-9.md
  relation: enhances
  description: SA-9.3 enhances base control SA-9.
nist_id: SA-9.3
sort_id: sa-09.03
implementation_level: organization
parameter_ids:
- sa-9.3_prm_1
- sa-09.03_odp.01
- sa-09.03_odp.02
reference_links:
- '#sa-9'
- '#sr-2'
---

# Summary

Establish, document, and maintain trust relationships with external service providers based on the following requirements, properties, factors, or conditions: {{ insert: param, sa-9.3_prm_1 }}.

# Statement

Establish, document, and maintain trust relationships with external service providers based on the following requirements, properties, factors, or conditions: {{ insert: param, sa-9.3_prm_1 }}.

# Guidance

Trust relationships between organizations and external service providers reflect the degree of confidence that the risk from using external services is at an acceptable level. Trust relationships can help organizations gain increased levels of confidence that service providers are providing adequate protection for the services rendered and can also be useful when conducting incident response or when planning for upgrades or obsolescence. Trust relationships can be complicated due to the potentially large number of entities participating in the consumer-provider interactions, subordinate relationships and levels of trust, and types of interactions between the parties. In some cases, the degree of trust is based on the level of control that organizations can exert on external service providers regarding the controls necessary for the protection of the service, information, or individual privacy and the evidence brought forth as to the effectiveness of the implemented controls. The level of control is established by the terms and conditions of the contracts or service-level agreements.

# Parameters

- `sa-9.3_prm_1`
- `sa-09.03_odp.01`
- `sa-09.03_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
