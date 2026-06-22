---
type: control
title: SR-2 - Supply Chain Risk Management Plan
description: SP 800-53 control SR-2.
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
- sr
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/sr.md
  relation: part_of
  description: SR-2 - Supply Chain Risk Management Plan is part of its parent SP 800-53 structure.
- name: SR-2.1 - Establish SCRM Team
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sr/sr-2.1.md
  relation: has_enhancement
  description: SR-2 has enhancement SR-2.1.
nist_id: SR-2
sort_id: sr-02
implementation_level: organization
parameter_ids:
- sr-02_odp.01
- sr-02_odp.02
reference_links:
- '#4ff10ed3-d8fe-4246-99e3-443045e27482'
- '#0f963c17-ab5a-432a-a867-91eac550309b'
- '#21caa535-1154-4369-ba7b-32c309fee0f7'
- '#031cc4b7-9adf-4835-98f1-f1ca493519cf'
- '#08b07465-dbdc-48d6-8a0b-37279602ac16'
- '#cec037f3-8aba-4c97-84b4-4082f9e515d2'
- '#e3cc0520-a366-4fc9-abc2-5272db7e3564'
- '#e8e84963-14fc-4c3a-be05-b412a5d37cd2'
- '#276bd50a-7e58-48e5-a405-8c8cb91d7a5f'
- '#e24b06cc-9129-4998-a76a-65c3d7a576ba'
- '#38ff38f0-1366-4f50-a4c9-26a39aacee16'
- '#ca-2'
- '#cp-4'
- '#ir-4'
- '#ma-2'
- '#ma-6'
- '#pe-16'
- '#pl-2'
- '#pm-9'
- '#pm-30'
- '#ra-3'
- '#ra-7'
- '#sa-8'
- '#si-4'
---

# Summary

SP 800-53 control SR-2.

# Statement

No statement text was present in the OSCAL record.

# Guidance

The dependence on products, systems, and services from external providers, as well as the nature of the relationships with those providers, present an increasing level of risk to an organization. Threat actions that may increase security or privacy risks include unauthorized production, the insertion or use of counterfeits, tampering, theft, insertion of malicious software and hardware, and poor manufacturing and development practices in the supply chain. Supply chain risks can be endemic or systemic within a system element or component, a system, an organization, a sector, or the Nation. Managing supply chain risk is a complex, multifaceted undertaking that requires a coordinated effort across an organization to build trust relationships and communicate with internal and external stakeholders. Supply chain risk management (SCRM) activities include identifying and assessing risks, determining appropriate risk response actions, developing SCRM plans to document response actions, and monitoring performance against plans. The SCRM plan (at the system-level) is implementation specific, providing policy implementation, requirements, constraints and implications. It can either be stand-alone, or incorporated into system security and privacy plans. The SCRM plan addresses managing, implementation, and monitoring of SCRM controls and the development/sustainment of systems across the SDLC to support mission and business functions.

Because supply chains can differ significantly across and within organizations, SCRM plans are tailored to the individual program, organizational, and operational contexts. Tailored SCRM plans provide the basis for determining whether a technology, service, system component, or system is fit for purpose, and as such, the controls need to be tailored accordingly. Tailored SCRM plans help organizations focus their resources on the most critical mission and business functions based on mission and business requirements and their risk environment. Supply chain risk management plans include an expression of the supply chain risk tolerance for the organization, acceptable supply chain risk mitigation strategies or controls, a process for consistently evaluating and monitoring supply chain risk, approaches for implementing and communicating the plan, a description of and justification for supply chain risk mitigation measures taken, and associated roles and responsibilities. Finally, supply chain risk management plans address requirements for developing trustworthy, secure, privacy-protective, and resilient system components and systems, including the application of the security design principles implemented as part of life cycle-based systems security engineering processes (see [SA-8](#sa-8)).

# Parameters

- `sr-02_odp.01`
- `sr-02_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
