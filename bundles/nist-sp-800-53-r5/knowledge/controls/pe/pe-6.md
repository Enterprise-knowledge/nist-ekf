---
type: control
title: PE-6 - Monitoring Physical Access
description: SP 800-53 control PE-6.
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
- pe
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/pe.md
  relation: part_of
  description: PE-6 - Monitoring Physical Access is part of its parent SP 800-53 structure.
- name: PE-6.1 - Intrusion Alarms and Surveillance Equipment
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-6.1.md
  relation: has_enhancement
  description: PE-6 has enhancement PE-6.1.
- name: PE-6.2 - Automated Intrusion Recognition and Responses
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-6.2.md
  relation: has_enhancement
  description: PE-6 has enhancement PE-6.2.
- name: PE-6.3 - Video Surveillance
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-6.3.md
  relation: has_enhancement
  description: PE-6 has enhancement PE-6.3.
- name: PE-6.4 - Monitoring Physical Access to Systems
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/pe/pe-6.4.md
  relation: has_enhancement
  description: PE-6 has enhancement PE-6.4.
nist_id: PE-6
sort_id: pe-06
implementation_level: organization
parameter_ids:
- pe-06_odp.01
- pe-06_odp.02
reference_links:
- '#au-2'
- '#au-6'
- '#au-9'
- '#au-12'
- '#ca-7'
- '#cp-10'
- '#ir-4'
- '#ir-8'
---

# Summary

SP 800-53 control PE-6.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Physical access monitoring includes publicly accessible areas within organizational facilities. Examples of physical access monitoring include the employment of guards, video surveillance equipment (i.e., cameras), and sensor devices. Reviewing physical access logs can help identify suspicious activity, anomalous events, or potential threats. The reviews can be supported by audit logging controls, such as [AU-2](#au-2) , if the access logs are part of an automated system. Organizational incident response capabilities include investigations of physical security incidents and responses to the incidents. Incidents include security violations or suspicious physical access activities. Suspicious physical access activities include accesses outside of normal work hours, repeated accesses to areas not normally accessed, accesses for unusual lengths of time, and out-of-sequence accesses.

# Parameters

- `pe-06_odp.01`
- `pe-06_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
