---
type: control_enhancement
title: SR-5.2 - Assessments Prior to Selection, Acceptance, Modification, or Update
description: Assess the system, system component, or system service prior to selection, acceptance, modification,
  or update.
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
- name: Base control
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-5.md
  relation: part_of
  description: SR-5.2 - Assessments Prior to Selection, Acceptance, Modification, or Update is part of its parent
    SP 800-53 structure.
- name: SR-5 - Acquisition Strategies, Tools, and Methods
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sr/sr-5.md
  relation: enhances
  description: SR-5.2 enhances base control SR-5.
nist_id: SR-5.2
sort_id: sr-05.02
implementation_level: organization
parameter_ids: []
reference_links:
- '#sr-5'
- '#ca-8'
- '#ra-5'
- '#sa-11'
- '#si-7'
---

# Summary

Assess the system, system component, or system service prior to selection, acceptance, modification, or update.

# Statement

Assess the system, system component, or system service prior to selection, acceptance, modification, or update.

# Guidance

Organizational personnel or independent, external entities conduct assessments of systems, components, products, tools, and services to uncover evidence of tampering, unintentional and intentional vulnerabilities, or evidence of non-compliance with supply chain controls. These include malicious code, malicious processes, defective software, backdoors, and counterfeits. Assessments can include evaluations; design proposal reviews; visual or physical inspection; static and dynamic analyses; visual, x-ray, or magnetic particle inspections; simulations; white, gray, or black box testing; fuzz testing; stress testing; and penetration testing (see [SR-6(1)](#sr-6.1) ). Evidence generated during assessments is documented for follow-on actions by organizations. The evidence generated during the organizational or independent assessments of supply chain elements may be used to improve supply chain processes and inform the supply chain risk management process. The evidence can be leveraged in follow-on assessments. Evidence and other documentation may be shared in accordance with organizational agreements.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
