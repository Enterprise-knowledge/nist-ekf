---
type: control_enhancement
title: CM-2.7 - Configure Systems and Components for High-risk Areas
description: SP 800-53 control CM-2.7.
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
- cm
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-2.md
  relation: part_of
  description: CM-2.7 - Configure Systems and Components for High-risk Areas is part of its parent SP 800-53 structure.
- name: CM-2 - Baseline Configuration
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-2.md
  relation: enhances
  description: CM-2.7 enhances base control CM-2.
nist_id: CM-2.7
sort_id: cm-02.07
implementation_level: organization
parameter_ids:
- cm-02.07_odp.01
- cm-02.07_odp.02
- cm-02.07_odp.03
reference_links:
- '#cm-2'
- '#mp-4'
- '#mp-5'
---

# Summary

SP 800-53 control CM-2.7.

# Statement

No statement text was present in the OSCAL record.

# Guidance

When it is known that systems or system components will be in high-risk areas external to the organization, additional controls may be implemented to counter the increased threat in such areas. For example, organizations can take actions for notebook computers used by individuals departing on and returning from travel. Actions include determining the locations that are of concern, defining the required configurations for the components, ensuring that components are configured as intended before travel is initiated, and applying controls to the components after travel is completed. Specially configured notebook computers include computers with sanitized hard drives, limited applications, and more stringent configuration settings. Controls applied to mobile devices upon return from travel include examining the mobile device for signs of physical tampering and purging and reimaging disk drives. Protecting information that resides on mobile devices is addressed in the [MP](#mp) (Media Protection) family.

# Parameters

- `cm-02.07_odp.01`
- `cm-02.07_odp.02`
- `cm-02.07_odp.03`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
