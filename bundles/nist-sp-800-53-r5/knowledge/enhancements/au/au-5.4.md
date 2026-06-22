---
type: control_enhancement
title: AU-5.4 - Shutdown on Failure
description: 'Invoke a {{ insert: param, au-05.04_odp.01 }} in the event of {{ insert: param, au-05.04_odp.02 }}
  , unless an alternate audit logging capability exists.'
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
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-5.md
  relation: part_of
  description: AU-5.4 - Shutdown on Failure is part of its parent SP 800-53 structure.
- name: AU-5 - Response to Audit Logging Process Failures
  path: /bundles/nist-sp-800-53-r5/knowledge/controls/au/au-5.md
  relation: enhances
  description: AU-5.4 enhances base control AU-5.
nist_id: AU-5.4
sort_id: au-05.04
implementation_level: system
parameter_ids:
- au-05.04_odp.01
- au-05.04_odp.02
reference_links:
- '#au-5'
- '#au-15'
---

# Summary

Invoke a {{ insert: param, au-05.04_odp.01 }} in the event of {{ insert: param, au-05.04_odp.02 }} , unless an alternate audit logging capability exists.

# Statement

Invoke a {{ insert: param, au-05.04_odp.01 }} in the event of {{ insert: param, au-05.04_odp.02 }} , unless an alternate audit logging capability exists.

# Guidance

Organizations determine the types of audit logging failures that can trigger automatic system shutdowns or degraded operations. Because of the importance of ensuring mission and business continuity, organizations may determine that the nature of the audit logging failure is not so severe that it warrants a complete shutdown of the system supporting the core organizational mission and business functions. In those instances, partial system shutdowns or operating in a degraded mode with reduced capability may be viable alternatives.

# Parameters

- `au-05.04_odp.01`
- `au-05.04_odp.02`

# Source Notes

This concept was generated from NIST OSCAL structured content and cites the local SP 800-53 PDF as the publication source.

# Citations

[1] [NIST SP 800-53 Rev. 5 PDF](/source/NIST.SP.800-53r5.pdf)
[2] [NIST OSCAL SP 800-53 catalog](/artifacts/data/NIST_SP-800-53_rev5_catalog.json)
