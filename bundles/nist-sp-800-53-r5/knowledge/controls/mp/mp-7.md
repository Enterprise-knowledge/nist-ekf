---
type: control
title: MP-7 - Media Use
description: SP 800-53 control MP-7.
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
- mp
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
  path: /bundles/nist-sp-800-53-r5/knowledge/families/mp.md
  relation: part_of
  description: MP-7 - Media Use is part of its parent SP 800-53 structure.
- name: MP-7.1 - Prohibit Use Without Owner
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-7.1.md
  relation: has_enhancement
  description: MP-7 has enhancement MP-7.1.
- name: MP-7.2 - Prohibit Use of Sanitization-resistant Media
  path: /bundles/nist-sp-800-53-r5/knowledge/enhancements/mp/mp-7.2.md
  relation: has_enhancement
  description: MP-7 has enhancement MP-7.2.
nist_id: MP-7
sort_id: mp-07
implementation_level: organization
parameter_ids:
- mp-07_odp.01
- mp-07_odp.02
- mp-07_odp.03
- mp-07_odp.04
reference_links:
- '#628d22a1-6a11-4784-bc59-5cd9497b5445'
- '#22f2d4f0-4365-4e88-a30d-275c1f5473ea'
- '#ac-19'
- '#ac-20'
- '#pl-4'
- '#pm-12'
- '#sc-34'
- '#sc-41'
---

# Summary

SP 800-53 control MP-7.

# Statement

No statement text was present in the OSCAL record.

# Guidance

System media includes both digital and non-digital media. Digital media includes diskettes, magnetic tapes, flash drives, compact discs, digital versatile discs, and removable hard disk drives. Non-digital media includes paper and microfilm. Media use protections also apply to mobile devices with information storage capabilities. In contrast to [MP-2](#mp-2) , which restricts user access to media, MP-7 restricts the use of certain types of media on systems, for example, restricting or prohibiting the use of flash drives or external hard disk drives. Organizations use technical and nontechnical controls to restrict the use of system media. Organizations may restrict the use of portable storage devices, for example, by using physical cages on workstations to prohibit access to certain external ports or disabling or removing the ability to insert, read, or write to such devices. Organizations may also limit the use of portable storage devices to only approved devices, including devices provided by the organization, devices provided by other approved organizations, and devices that are not personally owned. Finally, organizations may restrict the use of portable storage devices based on the type of device, such as by prohibiting the use of writeable, portable storage devices and implementing this restriction by disabling or removing the capability to write to such devices. Requiring identifiable owners for storage devices reduces the risk of using such devices by allowing organizations to assign responsibility for addressing known vulnerabilities in the devices.

# Parameters

- `mp-07_odp.01`
- `mp-07_odp.02`
- `mp-07_odp.03`
- `mp-07_odp.04`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
