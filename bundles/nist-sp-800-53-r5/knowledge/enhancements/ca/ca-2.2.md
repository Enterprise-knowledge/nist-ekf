---
type: control_enhancement
title: CA-2.2 - Specialized Assessments
description: 'Include as part of control assessments, {{ insert: param, ca-02.02_odp.01 }}, {{ insert: param, ca-02.02_odp.02
  }}, {{ insert: param, ca-02.02_odp.03 }}.'
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
- ca
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ca/ca-2.md
  relation: part_of
  description: CA-2.2 - Specialized Assessments is part of its parent SP 800-53 structure.
- name: CA-2 - Control Assessments
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ca/ca-2.md
  relation: enhances
  description: CA-2.2 enhances base control CA-2.
nist_id: CA-2.2
sort_id: ca-02.02
implementation_level: organization
parameter_ids:
- ca-02.02_odp.01
- ca-02.02_odp.02
- ca-02.02_odp.03
- ca-02.02_odp.04
reference_links:
- '#ca-2'
- '#pe-3'
- '#si-2'
---

# Summary

Include as part of control assessments, {{ insert: param, ca-02.02_odp.01 }}, {{ insert: param, ca-02.02_odp.02 }}, {{ insert: param, ca-02.02_odp.03 }}.

# Statement

Include as part of control assessments, {{ insert: param, ca-02.02_odp.01 }}, {{ insert: param, ca-02.02_odp.02 }}, {{ insert: param, ca-02.02_odp.03 }}.

# Guidance

Organizations can conduct specialized assessments, including verification and validation, system monitoring, insider threat assessments, malicious user testing, and other forms of testing. These assessments can improve readiness by exercising organizational capabilities and indicating current levels of performance as a means of focusing actions to improve security and privacy. Organizations conduct specialized assessments in accordance with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines. Authorizing officials approve the assessment methods in coordination with the organizational risk executive function. Organizations can include vulnerabilities uncovered during assessments into vulnerability remediation processes. Specialized assessments can also be conducted early in the system development life cycle (e.g., during initial design, development, and unit testing).

# Parameters

- `ca-02.02_odp.01`
- `ca-02.02_odp.02`
- `ca-02.02_odp.03`
- `ca-02.02_odp.04`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
