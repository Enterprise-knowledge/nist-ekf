---
type: control_enhancement
title: IR-4.10 - Supply Chain Coordination
description: Coordinate incident handling activities involving supply chain events with other organizations involved
  in the supply chain.
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
- ir
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-4.md
  relation: part_of
  description: IR-4.10 - Supply Chain Coordination is part of its parent SP 800-53 structure.
- name: IR-4 - Incident Handling
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/ir/ir-4.md
  relation: enhances
  description: IR-4.10 enhances base control IR-4.
nist_id: IR-4.10
sort_id: ir-04.10
implementation_level: organization
parameter_ids: []
reference_links:
- '#ir-4'
- '#ca-3'
- '#ma-2'
- '#sa-9'
- '#sr-8'
---

# Summary

Coordinate incident handling activities involving supply chain events with other organizations involved in the supply chain.

# Statement

Coordinate incident handling activities involving supply chain events with other organizations involved in the supply chain.

# Guidance

Organizations involved in supply chain activities include product developers, system integrators, manufacturers, packagers, assemblers, distributors, vendors, and resellers. Supply chain incidents can occur anywhere through or to the supply chain and include compromises or breaches that involve primary or sub-tier providers, information technology products, system components, development processes or personnel, and distribution processes or warehousing facilities. Organizations consider including processes for protecting and sharing incident information in information exchange agreements and their obligations for reporting incidents to government oversight bodies (e.g., Federal Acquisition Security Council).

# Parameters

No parameters were present in the OSCAL record.

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
