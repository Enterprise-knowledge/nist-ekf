---
type: control_enhancement
title: AT-2.4 - Suspicious Communications and Anomalous System Behavior
description: 'Provide literacy training on recognizing suspicious communications and anomalous behavior in organizational
  systems using {{ insert: param, at-02.04_odp }}.'
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
- at
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/at/at-2.md
  relation: part_of
  description: AT-2.4 - Suspicious Communications and Anomalous System Behavior is part of its parent SP 800-53
    structure.
- name: AT-2 - Literacy Training and Awareness
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/at/at-2.md
  relation: enhances
  description: AT-2.4 enhances base control AT-2.
nist_id: AT-2.4
sort_id: at-02.04
implementation_level: organization
parameter_ids:
- at-02.04_odp
reference_links:
- '#at-2'
---

# Summary

Provide literacy training on recognizing suspicious communications and anomalous behavior in organizational systems using {{ insert: param, at-02.04_odp }}.

# Statement

Provide literacy training on recognizing suspicious communications and anomalous behavior in organizational systems using {{ insert: param, at-02.04_odp }}.

# Guidance

A well-trained workforce provides another organizational control that can be employed as part of a defense-in-depth strategy to protect against malicious code coming into organizations via email or the web applications. Personnel are trained to look for indications of potentially suspicious email (e.g., receiving an unexpected email, receiving an email containing strange or poor grammar, or receiving an email from an unfamiliar sender that appears to be from a known sponsor or contractor). Personnel are also trained on how to respond to suspicious email or web communications. For this process to work effectively, personnel are trained and made aware of what constitutes suspicious communications. Training personnel on how to recognize anomalous behaviors in systems can provide organizations with early warning for the presence of malicious code. Recognition of anomalous behavior by organizational personnel can supplement malicious code detection and protection tools and systems employed by organizations.

# Parameters

- `at-02.04_odp`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
