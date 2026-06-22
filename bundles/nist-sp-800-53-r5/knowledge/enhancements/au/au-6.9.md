---
type: control_enhancement
title: AU-6.9 - Correlation with Information from Nontechnical Sources
description: Correlate information from nontechnical sources with audit record information to enhance organization-wide
  situational awareness.
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
- au
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-6.md
  relation: part_of
  description: AU-6.9 - Correlation with Information from Nontechnical Sources is part of its parent SP 800-53 structure.
- name: AU-6 - Audit Record Review, Analysis, and Reporting
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-6.md
  relation: enhances
  description: AU-6.9 enhances base control AU-6.
nist_id: AU-6.9
sort_id: au-06.09
implementation_level: organization
parameter_ids: []
reference_links:
- '#au-6'
- '#pm-12'
---

# Summary

Correlate information from nontechnical sources with audit record information to enhance organization-wide situational awareness.

# Statement

Correlate information from nontechnical sources with audit record information to enhance organization-wide situational awareness.

# Guidance

Nontechnical sources include records that document organizational policy violations related to harassment incidents and the improper use of information assets. Such information can lead to a directed analytical effort to detect potential malicious insider activity. Organizations limit access to information that is available from nontechnical sources due to its sensitive nature. Limited access minimizes the potential for inadvertent release of privacy-related information to individuals who do not have a need to know. The correlation of information from nontechnical sources with audit record information generally occurs only when individuals are suspected of being involved in an incident. Organizations obtain legal advice prior to initiating such actions.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
