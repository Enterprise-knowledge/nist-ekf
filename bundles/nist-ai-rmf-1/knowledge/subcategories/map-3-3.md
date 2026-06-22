---
type: framework_subcategory
title: MAP 3.3
description: Targeted application scope is specified and documented based on the system’s capability, established
  context, and AI system categorization.
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
- map-3-3
- context-of-use
- documentation
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
- name: MAP-3
  path: /bundles/nist-ai-rmf-1/knowledge/categories/map-3.md
  relation: part_of
  description: This Subcategory is part of AI RMF Category MAP-3.
nist_id: MAP 3.3
ai_actors:
- AI Design
- AI Development
- Human Factors
topics:
- Context of Use
- Documentation
---

# Summary

Targeted application scope is specified and documented based on the system’s capability, established context, and AI system categorization.

# Playbook About

Systems that function in a narrow scope tend to enable better mapping, measurement, and management of risks in the learning or decision-making tasks and the system context. A narrow application scope also helps ease TEVV functions and related resources within an organization.

For example, large language models or open-ended chatbot systems that interact with the public on the internet have a large number of risks that may be difficult to map, measure, and manage due to the variability from both the decision-making task and the operational context. Instead, a task-specific chatbot utilizing templated responses that follow a defined “user journey” is a scope that can be more easily mapped, measured and managed.

# Suggested Actions

- Consider narrowing contexts for system deployment, including factors related to:
        - How outcomes may directly or indirectly affect users, groups, communities and the environment.
        - Length of time the system is deployed in between re-trainings.
        - Geographical regions in which the system operates.
        - Dynamics related to community standards or likelihood of system misuse or abuses (either purposeful or unanticipated).
        - How AI system features and capabilities can be utilized within other applications, or in place of other existing processes.    
- Engage AI actors from legal and procurement functions when specifying target application scope.

# Documentation Prompts

### Organizations can document the following
- To what extent has the entity clearly defined technical specifications and requirements for the AI system?
- How do the technical specifications and requirements align with the AI system’s goals and objectives?

### AI Transparency Resources
- GAO-21-519SP: AI Accountability Framework for Federal Agencies & Other Entities. [URL](https://www.gao.gov/products/gao-21-519sp)
- Assessment List for Trustworthy AI (ALTAI) - The High-Level Expert Group on AI – 2019. [LINK](https://altai.insight-centre.org/), [URL](https://digital-strategy.ec.europa.eu/en/library/assessment-list-trustworthy-artificial-intelligence-altai-self-assessment)

# References

Mark J. Van der Laan and Sherri Rose (2018). Targeted Learning in Data Science. Cham: Springer International Publishing, 2018.

Alice Zheng. 2015. Evaluating Machine Learning Models (2015). O'Reilly. [URL](https://www.oreilly.com/library/view/evaluating-machine-learning/9781492048756/)

Brenda Leong and Patrick Hall (2021). 5 things lawyers should know about artificial intelligence. ABA Journal. [URL](https://www.abajournal.com/columns/article/5-things-lawyers-should-know-about-artificial-intelligence)

UK Centre for Data Ethics and Innovation, “The roadmap to an effective AI assurance ecosystem”. [URL](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/1039146/The_roadmap_to_an_effective_AI_assurance_ecosystem.pdf)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
