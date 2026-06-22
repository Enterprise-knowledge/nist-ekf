---
type: control_enhancement
title: CM-8.3 - Automated Unauthorized Component Detection
description: SP 800-53 control CM-8.3.
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-8.md
  relation: part_of
  description: CM-8.3 - Automated Unauthorized Component Detection is part of its parent SP 800-53 structure.
- name: CM-8 - System Component Inventory
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/cm/cm-8.md
  relation: enhances
  description: CM-8.3 enhances base control CM-8.
nist_id: CM-8.3
sort_id: cm-08.03
implementation_level: organization
parameter_ids:
- cm-8.3_prm_1
- cm-08.03_odp.01
- cm-08.03_odp.02
- cm-08.03_odp.03
- cm-08.03_odp.04
- cm-08.03_odp.05
- cm-08.03_odp.06
reference_links:
- '#cm-8'
- '#ac-19'
- '#ca-7'
- '#ra-5'
- '#sc-3'
- '#sc-39'
- '#sc-44'
- '#si-3'
- '#si-4'
- '#si-7'
---

# Summary

SP 800-53 control CM-8.3.

# Statement

No statement text was present in the OSCAL record.

# Guidance

Automated unauthorized component detection is applied in addition to the monitoring for unauthorized remote connections and mobile devices. Monitoring for unauthorized system components may be accomplished on an ongoing basis or by the periodic scanning of systems for that purpose. Automated mechanisms may also be used to prevent the connection of unauthorized components (see [CM-7(9)](#cm-7.9) ). Automated mechanisms can be implemented in systems or in separate system components. When acquiring and implementing automated mechanisms, organizations consider whether such mechanisms depend on the ability of the system component to support an agent or supplicant in order to be detected since some types of components do not have or cannot support agents (e.g., IoT devices, sensors). Isolation can be achieved , for example, by placing unauthorized system components in separate domains or subnets or quarantining such components. This type of component isolation is commonly referred to as "sandboxing."

# Parameters

- `cm-8.3_prm_1`
- `cm-08.03_odp.01`
- `cm-08.03_odp.02`
- `cm-08.03_odp.03`
- `cm-08.03_odp.04`
- `cm-08.03_odp.05`
- `cm-08.03_odp.06`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
