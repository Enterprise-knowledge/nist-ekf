---
type: framework_subcategory
title: MAP 5.1
description: Likelihood and magnitude of each identified impact (both potentially beneficial and harmful) based
  on expected use, past uses of AI systems in similar contexts, public incident reports, feedback from those external
  to the team that developed or deployed the AI system, or other data are identified and documented.
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
- map-5-1
- participation
- impact-assessment
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
- name: MAP-5
  path: /bundles/nist-ai-rmf-1/knowledge/categories/map-5.md
  relation: part_of
  description: This Subcategory is part of AI RMF Category MAP-5.
nist_id: MAP 5.1
ai_actors:
- AI Design
- AI Development
- AI Deployment
- AI Impact Assessment
- Operation and Monitoring
- Affected Individuals and Communities
- End-Users
topics:
- Participation
- Impact Assessment
---

# Summary

Likelihood and magnitude of each identified impact (both potentially beneficial and harmful) based on expected use, past uses of AI systems in similar contexts, public incident reports, feedback from those external to the team that developed or deployed the AI system, or other data are identified and documented.

# Playbook About

AI actors can evaluate, document and triage the likelihood of AI system impacts identified in Map 5.1 Likelihood estimates may then be assessed and judged for go/no-go decisions about deploying an AI system. If an organization decides to proceed with deploying the system, the likelihood and magnitude estimates can be used to assign TEVV resources appropriate for the risk level.

# Suggested Actions

- Establish assessment scales for measuring AI systems’ impact. Scales may be qualitative, such as red-amber-green (RAG), or may entail simulations or econometric approaches. Document and apply scales uniformly across the organization’s AI portfolio.
- Apply TEVV regularly at key stages in the AI lifecycle, connected to system impacts and frequency of system updates.
- Identify and document  likelihood and magnitude of system benefits and negative impacts in relation to trustworthiness characteristics.
- Establish processes for red teaming to identify and connect system limitations to AI lifecycle stage(s) and potential downstream impacts

# Documentation Prompts

### Organizations can document the following
- Which population(s) does the AI system impact?
- What assessments has the entity conducted on trustworthiness characteristics for example data security and privacy impacts associated with the AI system?
- Can the AI system be tested by independent third parties?

### AI Transparency Resources
- Datasheets for Datasets. [URL](http://arxiv.org/abs/1803.09010)
- GAO-21-519SP: AI Accountability Framework for Federal Agencies & Other Entities. [URL](https://www.gao.gov/products/gao-21-519sp)
- AI policies and initiatives, in Artificial Intelligence in Society, OECD, 2019. [URL](https://www.oecd.org/publications/artificial-intelligence-in-society-eedfee77-en.htm)
- Intel.gov: AI Ethics Framework for Intelligence Community  - 2020. [URL](https://www.intelligence.gov/artificial-intelligence-ethics-framework-for-the-intelligence-community)
- Assessment List for Trustworthy AI (ALTAI) - The High-Level Expert Group on AI - 2019. [LINK](https://altai.insight-centre.org/), [URL](https://digital-strategy.ec.europa.eu/en/library/assessment-list-trustworthy-artificial-intelligence-altai-self-assessment)

# References

Emilio Gómez-González and Emilia Gómez. 2020. Artificial intelligence in medicine and healthcare. Joint Research Centre (European Commission). [URL](https://op.europa.eu/en/publication-detail/-/publication/b4b5db47-94c0-11ea-aac4-01aa75ed71a1/language-en)

Artificial Intelligence Incident Database. 2022. [URL](https://incidentdatabase.ai/?lang=en)

Anthony M. Barrett, Dan Hendrycks, Jessica Newman and Brandie Nonnecke. “Actionable Guidance for High-Consequence AI Risk Management: Towards Standards Addressing AI Catastrophic Risks". ArXiv abs/2206.08966 (2022) [URL](https://arxiv.org/abs/2206.08966)

Ganguli, D., et al. (2022). Red Teaming Language Models to Reduce Harms: Methods, Scaling Behaviors, and Lessons Learned. arXiv. https://arxiv.org/abs/2209.07858

Upol Ehsan, Q. Vera Liao, Samir Passi, Mark O. Riedl, and Hal Daumé. 2024. Seamful XAI: Operationalizing Seamful Design in Explainable AI. Proc. ACM Hum.-Comput. Interact. 8, CSCW1, Article 119. https://doi.org/10.1145/3637396

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
