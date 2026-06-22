---
type: framework_subcategory
title: GOVERN 4.3
description: Organizational practices are in place to enable AI testing, identification of incidents, and information
  sharing.
status: active
owner:
  name: Enterprise Knowledge Format Maintainers
updated: '2026-06-22T00:00:00Z'
domain: ai-risk-management
system: nist-ai-rmf-1
tags:
- nist
- ai-rmf
- subcategory
- govern-4-3
- risk-culture
- governance
- ai-incidents
- impact-assessment
- drift
- fairness-and-bias
confidence: high
review:
  status: agent-generated
  reviewed_by: EKF generation workflow
  reviewed_at: '2026-06-22T00:00:00Z'
sources:
- name: NIST AI RMF 1.0 PDF
  path: /source/NIST.AI.100-1.pdf
  kind: pdf
  description: Local source PDF for AI RMF 1.0.
- name: NIST AI RMF Playbook JSON
  path: /artifacts/data/ai-rmf-playbook.json
  kind: json
  description: NIST AI RMF Playbook JSON with subcategory-aligned suggestions.
related:
- name: GOVERN-4
  path: /bundles/nist-ai-rmf-1/knowledge/categories/govern-4.md
  relation: part_of
  description: This Subcategory is part of AI RMF Category GOVERN-4.
nist_id: GOVERN 4.3
ai_actors:
- TEVV
- Operation and Monitoring
- Governance and Oversight
- Fairness and Bias
topics:
- Risk Culture
- Governance
- AI Incidents
- Impact Assessment
- Drift
- Fairness and Bias
---

# Summary

Organizational practices are in place to enable AI testing, identification of incidents, and information sharing.

# Playbook About

Identifying AI system limitations, detecting and tracking negative impacts and incidents, and sharing information about these issues with appropriate AI actors will improve risk management. Issues such as concept drift, AI bias and discrimination, shortcut learning or underspecification are difficult to identify using current standard AI testing processes. Organizations can institute in-house use and testing policies and procedures to identify and manage such issues. Efforts can take the form of pre-alpha or pre-beta testing, or deploying internally developed systems or products within the organization. Testing may entail limited and controlled in-house, or publicly available, AI system testbeds, and accessibility of AI system interfaces and outputs.

Without policies and procedures that enable consistent testing practices, risk management efforts may be bypassed or ignored, exacerbating risks or leading to inconsistent risk management activities.

Information sharing about impacts or incidents detected during testing or deployment can:

* draw attention to AI system risks, failures, abuses or misuses, 
* allow organizations to benefit from insights based on a wide range of AI applications and implementations, and 
* allow organizations to be more proactive in avoiding known failure modes.

Organizations may consider sharing incident information with the AI Incident Database, the AIAAIC, users, impacted communities, or with traditional cyber vulnerability databases, such as the MITRE CVE list.

# Suggested Actions

- Establish policies and procedures to facilitate and equip AI system testing.
- Establish organizational commitment to identifying AI system limitations and sharing of insights about limitations within appropriate AI actor groups.
- Establish policies for reporting and documenting incident response.
- Establish policies and processes regarding public disclosure of incidents and information sharing.
- Establish guidelines for incident handling related to AI system risks and performance.

# Documentation Prompts

### Organizations can document the following
- Did your organization address usability problems and test whether user interfaces served their intended purposes? Consulting the community or end users at the earliest stages of development to ensure there is transparency on the technology used and how it is deployed.
- Did your organization implement a risk management system to address risks involved in deploying the identified AI solution (e.g. personnel risk or changes to commercial objectives)?
- To what extent can users or parties affected by the outputs of the AI system test the AI system and provide feedback?

### AI Transparency Resources
- WEF Model AI Governance Framework Assessment 2020. [URL](https://www.pdpc.gov.sg/-/media/Files/PDPC/PDF-Files/Resource-for-Organisation/AI/SGModelAIGovFramework2.pdf)
- WEF Companion to the Model AI Governance Framework- 2020. [URL](https://www.pdpc.gov.sg/-/media/Files/PDPC/PDF-Files/Resource-for-Organisation/AI/SGIsago.pdf)

# References

Sean McGregor, “Preventing Repeated Real World AI Failures by Cataloging Incidents: The AI Incident Database,” arXiv:2011.08512 [cs], Nov. 2020, arXiv:2011.08512. [URL](http://arxiv.org/abs/2011.08512)

Christopher Johnson, Mark Badger, David Waltermire, Julie Snyder, and Clem Skorupka,  “Guide to cyber threat information sharing,” National Institute of Standards and Technology, NIST Special Publication 800-150, Nov 2016. [URL](https://doi.org/10.6028/NIST.SP.800-150)

Mengyi Wei, Zhixuan Zhou (2022). AI Ethics Issues in Real World: Evidence from AI Incident Database. ArXiv, abs/2206.07635. [URL](https://arxiv.org/pdf/2206.07635.pdf)

BSA The Software Alliance (2021) Confronting Bias: BSA’s Framework to Build Trust in AI. [URL](https://www.bsa.org/reports/confronting-bias-bsas-framework-to-build-trust-in-ai)

“Using Combined Expertise to Evaluate Web Accessibility,” W3C Web Accessibility Initiative. [URL](https://www.w3.org/WAI/test-evaluate/combined-expertise/)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
