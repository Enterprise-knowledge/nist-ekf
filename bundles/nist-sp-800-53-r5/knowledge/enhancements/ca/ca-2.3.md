---
type: control_enhancement
title: CA-2.3 - Leveraging Results from External Organizations
description: 'Leverage the results of control assessments performed by {{ insert: param, ca-02.03_odp.01 }} on {{
  insert: param, ca-02.03_odp.02 }} when the assessment meets {{ insert: param, ca-02.03_odp.03 }}.'
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
  description: CA-2.3 - Leveraging Results from External Organizations is part of its parent SP 800-53 structure.
- name: CA-2 - Control Assessments
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ca/ca-2.md
  relation: enhances
  description: CA-2.3 enhances base control CA-2.
nist_id: CA-2.3
sort_id: ca-02.03
implementation_level: organization
parameter_ids:
- ca-02.03_odp.01
- ca-02.03_odp.02
- ca-02.03_odp.03
reference_links:
- '#ca-2'
- '#sa-4'
---

# Summary

Leverage the results of control assessments performed by {{ insert: param, ca-02.03_odp.01 }} on {{ insert: param, ca-02.03_odp.02 }} when the assessment meets {{ insert: param, ca-02.03_odp.03 }}.

# Statement

Leverage the results of control assessments performed by {{ insert: param, ca-02.03_odp.01 }} on {{ insert: param, ca-02.03_odp.02 }} when the assessment meets {{ insert: param, ca-02.03_odp.03 }}.

# Guidance

Organizations may rely on control assessments of organizational systems by other (external) organizations. Using such assessments and reusing existing assessment evidence can decrease the time and resources required for assessments by limiting the independent assessment activities that organizations need to perform. The factors that organizations consider in determining whether to accept assessment results from external organizations can vary. Such factors include the organization’s past experience with the organization that conducted the assessment, the reputation of the assessment organization, the level of detail of supporting assessment evidence provided, and mandates imposed by applicable laws, executive orders, directives, regulations, policies, standards, and guidelines. Accredited testing laboratories that support the Common Criteria Program [ISO 15408-1](#6afc1b04-c9d6-4023-adbc-f8fbe33a3c73) , the NIST Cryptographic Module Validation Program (CMVP), or the NIST Cryptographic Algorithm Validation Program (CAVP) can provide independent assessment results that organizations can leverage.

# Parameters

- `ca-02.03_odp.01`
- `ca-02.03_odp.02`
- `ca-02.03_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
