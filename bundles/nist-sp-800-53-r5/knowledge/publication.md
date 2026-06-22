---
type: publication
title: NIST SP 800-53 Rev. 5 - Security and Privacy Controls
description: NIST publication providing a catalog of security and privacy controls for information systems and organizations.
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: security-and-privacy-controls
system: nist-sp-800-53-r5
tags:
- nist
- sp800-53
- controls
- security
- privacy
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
- name: Access Control
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ac.md
  relation: contains
  description: The publication contains the Access Control control family.
- name: Awareness and Training
  path: /bundles/nist-sp-800-53-r5/knowledge/families/at.md
  relation: contains
  description: The publication contains the Awareness and Training control family.
- name: Audit and Accountability
  path: /bundles/nist-sp-800-53-r5/knowledge/families/au.md
  relation: contains
  description: The publication contains the Audit and Accountability control family.
- name: Assessment, Authorization, and Monitoring
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ca.md
  relation: contains
  description: The publication contains the Assessment, Authorization, and Monitoring control family.
- name: Configuration Management
  path: /bundles/nist-sp-800-53-r5/knowledge/families/cm.md
  relation: contains
  description: The publication contains the Configuration Management control family.
- name: Contingency Planning
  path: /bundles/nist-sp-800-53-r5/knowledge/families/cp.md
  relation: contains
  description: The publication contains the Contingency Planning control family.
- name: Identification and Authentication
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ia.md
  relation: contains
  description: The publication contains the Identification and Authentication control family.
- name: Incident Response
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ir.md
  relation: contains
  description: The publication contains the Incident Response control family.
- name: Maintenance
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ma.md
  relation: contains
  description: The publication contains the Maintenance control family.
- name: Media Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/families/mp.md
  relation: contains
  description: The publication contains the Media Protection control family.
- name: Physical and Environmental Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/families/pe.md
  relation: contains
  description: The publication contains the Physical and Environmental Protection control family.
- name: Planning
  path: /bundles/nist-sp-800-53-r5/knowledge/families/pl.md
  relation: contains
  description: The publication contains the Planning control family.
- name: Program Management
  path: /bundles/nist-sp-800-53-r5/knowledge/families/pm.md
  relation: contains
  description: The publication contains the Program Management control family.
- name: Personnel Security
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ps.md
  relation: contains
  description: The publication contains the Personnel Security control family.
- name: Personally Identifiable Information Processing and Transparency
  path: /bundles/nist-sp-800-53-r5/knowledge/families/pt.md
  relation: contains
  description: The publication contains the Personally Identifiable Information Processing and Transparency control
    family.
- name: Risk Assessment
  path: /bundles/nist-sp-800-53-r5/knowledge/families/ra.md
  relation: contains
  description: The publication contains the Risk Assessment control family.
- name: System and Services Acquisition
  path: /bundles/nist-sp-800-53-r5/knowledge/families/sa.md
  relation: contains
  description: The publication contains the System and Services Acquisition control family.
- name: System and Communications Protection
  path: /bundles/nist-sp-800-53-r5/knowledge/families/sc.md
  relation: contains
  description: The publication contains the System and Communications Protection control family.
- name: System and Information Integrity
  path: /bundles/nist-sp-800-53-r5/knowledge/families/si.md
  relation: contains
  description: The publication contains the System and Information Integrity control family.
- name: Supply Chain Risk Management
  path: /bundles/nist-sp-800-53-r5/knowledge/families/sr.md
  relation: contains
  description: The publication contains the Supply Chain Risk Management control family.
artifacts:
- name: SP 800-53 PDF markdown extraction
  path: /artifacts/markdown/documents/NIST.SP.800-53r5.md
  kind: markdown
  description: Full page-marked markdown extraction of NIST.SP.800-53r5.pdf.
oscal_version: 5.2.0
---

# Summary

NIST SP 800-53 Rev. 5 provides a catalog of security and privacy controls. This EKF bundle represents 20 control families, 324 base controls, and 872 control enhancements from NIST's OSCAL catalog, while preserving the local PDF as source provenance.

# Source Notes

The local PDF is the requested source publication. The OSCAL catalog is a NIST-maintained machine-readable representation used to generate precise control and enhancement concepts. When the OSCAL release contains later patch-level changes, the concept provenance makes that enrichment explicit.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
