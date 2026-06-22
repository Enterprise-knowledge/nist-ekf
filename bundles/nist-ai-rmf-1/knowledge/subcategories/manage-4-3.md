---
type: framework_subcategory
title: MANAGE 4.3
description: Incidents and errors are communicated to relevant AI actors including affected communities. Processes
  for tracking, responding to, and recovering from incidents and errors are followed and documented.
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
- manage-4-3
- ai-incidents
- monitoring
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
- name: MANAGE-4
  path: /bundles/nist-ai-rmf-1/knowledge/categories/manage-4.md
  relation: part_of
  description: This Subcategory is part of AI RMF Category MANAGE-4.
nist_id: MANAGE 4.3
ai_actors:
- AI Deployment
- Operation and Monitoring
- End-Users
- Human Factors
- Domain Experts
- Affected Individuals and Communities
topics:
- AI Incidents
- Monitoring
---

# Summary

Incidents and errors are communicated to relevant AI actors including affected communities. Processes for tracking, responding to, and recovering from incidents and errors are followed and documented.

# Playbook About

Regularly documenting an accurate and transparent account of identified and reported errors can enhance AI risk management activities., Examples include:

- how errors were identified, 
- incidents related to the error, 
- whether the error has been repaired, and
- how repairs can be distributed to all impacted stakeholders and users.

# Suggested Actions

- Establish procedures to regularly share information about errors, incidents and negative impacts with relevant stakeholders, operators, practitioners and users, and impacted parties.
- Maintain a database of reported errors, near-misses, incidents and negative impacts including date reported, number of reports, assessment of impact and severity, and responses.
- Maintain a database of system changes, reason for change, and details of how the change was made, tested and deployed. 
- Maintain version history information and metadata to enable continuous improvement processes.
- Verify that relevant AI actors responsible for identifying complex or emergent risks are properly resourced and empowered.

# Documentation Prompts

### Organizations can document the following

- What corrective actions has the entity taken to enhance the quality, accuracy, reliability, and representativeness of the data?
- To what extent does the entity communicate its AI strategic goals and objectives to the community of stakeholders? How easily accessible and current is the information available to external stakeholders?
- What type of information is accessible on the design, operations, and limitations of the AI system to external stakeholders, including end users, consumers, regulators, and individuals impacted by use of the AI system?

### AI Transparency Resources

- GAO-21-519SP: Artificial Intelligence: An Accountability Framework for Federal Agencies & Other Entities, [URL](https://www.gao.gov/products/gao-21-519sp)

# References

Wei, M., & Zhou, Z. (2022). AI Ethics Issues in Real World: Evidence from AI Incident Database. ArXiv, abs/2206.07635. [URL](https://arxiv.org/pdf/2206.07635.pdf)

McGregor, Sean. "Preventing repeated real world AI failures by cataloging incidents: The AI incident database." Proceedings of the AAAI Conference on Artificial Intelligence. Vol. 35. No. 17. 2021. [URL](https://arxiv.org/pdf/2011.08512.pdf)

Macrae, Carl. "Learning from the failure of autonomous and intelligent systems: Accidents, safety, and sociotechnical sources of risk." Risk analysis 42.9 (2022): 1999-2025. [URL](https://onlinelibrary.wiley.com/doi/epdf/10.1111/risa.13850)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
