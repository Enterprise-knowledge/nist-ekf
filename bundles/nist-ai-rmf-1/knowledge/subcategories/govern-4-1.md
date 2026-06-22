---
type: framework_subcategory
title: GOVERN 4.1
description: Organizational policies, and practices are in place to foster a critical thinking and safety-first
  mindset in the design, development, deployment, and uses of AI systems to minimize negative impacts.
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
- govern-4-1
- risk-culture
- governance
- adversarial
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
nist_id: GOVERN 4.1
ai_actors:
- AI Design
- AI Development
- AI Deployment
- Operation and Monitoring
topics:
- Risk Culture
- Governance
- Adversarial
---

# Summary

Organizational policies, and practices are in place to foster a critical thinking and safety-first mindset in the design, development, deployment, and uses of AI systems to minimize negative impacts.

# Playbook About

A risk culture and accompanying practices can help organizations effectively triage the most critical risks. Organizations in some industries implement three (or more) “lines of defense,” where separate teams are held accountable for different aspects of the system lifecycle, such as development, risk management, and auditing. While a traditional three-lines approach may be impractical for smaller organizations, leadership can commit to cultivating a strong risk culture through other means. For example, “effective challenge,” is a culture- based practice that encourages critical thinking and questioning of important design and implementation decisions by experts with the authority and stature to make such changes.

Red-teaming is another risk measurement and management approach. This practice consists of adversarial testing of AI systems under stress conditions to seek out failure modes or vulnerabilities in the system. Red-teams are composed of external experts or personnel who are independent from internal AI actors.

# Suggested Actions

- Establish policies that require inclusion of oversight functions (legal, compliance, risk management) from the outset of the system design process.
- Establish policies that promote effective challenge of AI system design, implementation, and deployment decisions, via mechanisms such as the three lines of defense, model audits, or red-teaming – to minimize workplace risks such as groupthink.
- Establish policies that incentivize safety-first mindset and general critical thinking and review at an organizational and procedural level.
- Establish whistleblower protections for insiders who report on perceived serious problems with AI systems.
- Establish policies to integrate a harm and risk prevention mindset throughout the AI lifecycle.

# Documentation Prompts

### Organizations can document the following
- To what extent has the entity documented the AI system’s development, testing methodology, metrics, and performance outcomes?
- Are organizational information sharing practices widely followed and transparent, such that related past failed designs can be avoided? 
- Are training manuals and other resources for carrying out incident response documented and available? 
- Are processes for operator reporting of incidents and near-misses documented and available?
- How might revealing mismatches between claimed and actual system performance help users understand limitations and anticipate risks and impacts?”


### AI Transparency Resources
- Datasheets for Datasets. [URL](http://arxiv.org/abs/1803.09010)
- GAO-21-519SP: AI Accountability Framework for Federal Agencies & Other Entities. [URL](https://www.gao.gov/products/gao-21-519sp)
- WEF Model AI Governance Framework Assessment 2020. [URL](https://www.pdpc.gov.sg/-/media/Files/PDPC/PDF-Files/Resource-for-Organisation/AI/SGModelAIGovFramework2.pdf)

# References

Bd. Governors Fed. Rsrv. Sys., Supervisory Guidance on Model Risk Management, SR Letter 11-7 (Apr. 4, 2011)

Patrick Hall, Navdeep Gill, and Benjamin Cox, “Responsible Machine Learning,” O’Reilly Media, 2020. [URL](https://www.oreilly.com/library/view/responsible-machine-learning/9781492090878/)

Off. Superintendent Fin. Inst. Canada, Enterprise-Wide Model Risk Management for Deposit-Taking Institutions, E-23 (Sept. 2017).

GAO, “Artificial Intelligence: An Accountability Framework for Federal Agencies and Other Entities,” GAO@100 (GAO-21-519SP), June 2021. [URL](https://www.gao.gov/assets/gao-21-519sp.pdf)

Donald Sull, Stefano Turconi, and Charles Sull, “When It Comes to Culture, Does Your Company Walk the Talk?” MIT Sloan Mgmt. Rev., 2020. [URL](https://sloanreview.mit.edu/article/when-it-comes-to-culture-does-your-company-walk-the-talk)

Kathy Baxter, AI Ethics Maturity Model, Salesforce. [URL](https://www.salesforceairesearch.com/static/ethics/EthicalAIMaturityModel.pdf)

Upol Ehsan, Q. Vera Liao, Samir Passi, Mark O. Riedl, and Hal Daumé. 2024. Seamful XAI: Operationalizing Seamful Design in Explainable AI. Proc. ACM Hum.-Comput. Interact. 8, CSCW1, Article 119. https://doi.org/10.1145/3637396

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
