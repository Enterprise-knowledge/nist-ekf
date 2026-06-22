---
type: control
title: SA-5 - System Documentation
description: SP 800-53 control SA-5.
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
- name: Control family
  path: /bundles/nist-sp-800-53-r5/knowledge/families/sa.md
  relation: part_of
  description: SA-5 - System Documentation is part of its parent SP 800-53 structure.
- name: SA-5.1 - Functional Properties of Security Controls
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-5.1.md
  relation: has_enhancement
  description: SA-5 has enhancement SA-5.1.
- name: SA-5.2 - Security-relevant External System Interfaces
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-5.2.md
  relation: has_enhancement
  description: SA-5 has enhancement SA-5.2.
- name: SA-5.3 - High-level Design
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-5.3.md
  relation: has_enhancement
  description: SA-5 has enhancement SA-5.3.
- name: SA-5.4 - Low-level Design
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-5.4.md
  relation: has_enhancement
  description: SA-5 has enhancement SA-5.4.
- name: SA-5.5 - Source Code
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/sa/sa-5.5.md
  relation: has_enhancement
  description: SA-5 has enhancement SA-5.5.
nist_id: SA-5
sort_id: sa-05
implementation_level: organization
parameter_ids:
- sa-05_odp.01
- sa-05_odp.02
reference_links:
- '#e3cc0520-a366-4fc9-abc2-5272db7e3564'
- '#cm-4'
- '#cm-6'
- '#cm-7'
- '#cm-8'
- '#pl-2'
- '#pl-4'
- '#pl-8'
- '#ps-2'
- '#sa-3'
- '#sa-4'
- '#sa-8'
- '#sa-9'
- '#sa-10'
- '#sa-11'
- '#sa-15'
- '#sa-16'
- '#sa-17'
- '#si-12'
- '#sr-3'
---

# Summary

SP 800-53 control SA-5.

# Statement

No statement text was present in the OSCAL record.

# Guidance

System artifacts and documentation created by the developer helps organizational personnel understand the implementation and operation of controls. Organizations consider establishing specific measures to determine the quality and completeness of the content provided. System documentation may be used to delineate roles, responsibilities and expectations of the developer and organization, support the management of supply chain risk, incident response, flaw remediation, and other functions. Personnel or roles that require documentation include system owners, system security officers, and system administrators. Attempts to obtain documentation include contacting manufacturers or suppliers and conducting web-based searches. The inability to obtain documentation may occur due to the age of the system or component or the lack of support from developers and contractors. When documentation cannot be obtained, organizations may need to recreate the documentation if it is essential to the implementation or operation of the controls. The protection provided for the documentation is commensurate with the security category or classification of the system. Documentation that addresses system vulnerabilities may require an increased level of protection. Secure operation of the system includes initially starting the system and resuming secure system operation after a lapse in system operation. An example of least privilege in software development is minimizing the functions that operate with elevated privileges (e.g., limiting the tools and functionality that operate in kernel mode)

# Parameters

- `sa-05_odp.01`
- `sa-05_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
