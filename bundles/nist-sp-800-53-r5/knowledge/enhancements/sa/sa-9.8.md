---
type: control_enhancement
title: SA-9.8 - Processing and Storage Location — U.S. Jurisdiction
description: Restrict the geographic location of information processing and data storage to facilities located within
  in the legal jurisdictional boundary of the United States.
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
  description: SA-9.8 - Processing and Storage Location — U.S. Jurisdiction is part of its parent SP 800-53 structure.
- name: SA-9 - External System Services
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/sa/sa-9.md
  relation: enhances
  description: SA-9.8 enhances base control SA-9.
nist_id: SA-9.8
sort_id: sa-09.08
implementation_level: organization
parameter_ids: []
reference_links:
- '#sa-9'
- '#sa-5'
- '#sr-4'
---

# Summary

Restrict the geographic location of information processing and data storage to facilities located within in the legal jurisdictional boundary of the United States.

# Statement

Restrict the geographic location of information processing and data storage to facilities located within in the legal jurisdictional boundary of the United States.

# Guidance

The geographic location of information processing and data storage can have a direct impact on the ability of organizations to successfully execute their mission and business functions. A compromise or breach of high impact information and systems can have severe or catastrophic adverse impacts on organizational assets and operations, individuals, other organizations, and the Nation. Restricting the processing and storage of high-impact information to facilities within the legal jurisdictional boundary of the United States provides greater control over such processing and storage.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
