---
type: control_enhancement
title: CP-4.2 - Alternate Processing Site
description: 'Test the contingency plan at the alternate processing site:'
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
- cp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-4.md
  relation: part_of
  description: CP-4.2 - Alternate Processing Site is part of its parent SP 800-53 structure.
- name: CP-4 - Contingency Plan Testing
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cp/cp-4.md
  relation: enhances
  description: CP-4.2 enhances base control CP-4.
nist_id: CP-4.2
sort_id: cp-04.02
implementation_level: organization
parameter_ids: []
reference_links:
- '#cp-4'
- '#cp-7'
---

# Summary

Test the contingency plan at the alternate processing site:

# Statement

Test the contingency plan at the alternate processing site:

# Guidance

Conditions at the alternate processing site may be significantly different than the conditions at the primary site. Having the opportunity to visit the alternate site and experience the actual capabilities available at the site can provide valuable information on potential vulnerabilities that could affect essential organizational mission and business functions. The on-site visit can also provide an opportunity to refine the contingency plan to address the vulnerabilities discovered during testing.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
