---
type: control_enhancement
title: RA-2.1 - Impact-level Prioritization
description: Conduct an impact-level prioritization of organizational systems to obtain additional granularity on
  system impact levels.
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
- ra
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-2.md
  relation: part_of
  description: RA-2.1 - Impact-level Prioritization is part of its parent SP 800-53 structure.
- name: RA-2 - Security Categorization
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ra/ra-2.md
  relation: enhances
  description: RA-2.1 enhances base control RA-2.
nist_id: RA-2.1
sort_id: ra-02.01
implementation_level: organization
parameter_ids: []
reference_links:
- '#ra-2'
---

# Summary

Conduct an impact-level prioritization of organizational systems to obtain additional granularity on system impact levels.

# Statement

Conduct an impact-level prioritization of organizational systems to obtain additional granularity on system impact levels.

# Guidance

Organizations apply the "high-water mark" concept to each system categorized in accordance with [FIPS 199](#628d22a1-6a11-4784-bc59-5cd9497b5445) , resulting in systems designated as low impact, moderate impact, or high impact. Organizations that desire additional granularity in the system impact designations for risk-based decision-making, can further partition the systems into sub-categories of the initial system categorization. For example, an impact-level prioritization on a moderate-impact system can produce three new sub-categories: low-moderate systems, moderate-moderate systems, and high-moderate systems. Impact-level prioritization and the resulting sub-categories of the system give organizations an opportunity to focus their investments related to security control selection and the tailoring of control baselines in responding to identified risks. Impact-level prioritization can also be used to determine those systems that may be of heightened interest or value to adversaries or represent a critical loss to the federal enterprise, sometimes described as high value assets. For such high value assets, organizations may be more focused on complexity, aggregation, and information exchanges. Systems with high value assets can be prioritized by partitioning high-impact systems into low-high systems, moderate-high systems, and high-high systems. Alternatively, organizations can apply the guidance in [CNSSI 1253](#4e4fbc93-333d-45e6-a875-de36b878b6b9) for security objective-related categorization.

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
