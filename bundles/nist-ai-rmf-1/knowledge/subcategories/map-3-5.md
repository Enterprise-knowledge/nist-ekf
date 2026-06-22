---
type: framework_subcategory
title: MAP 3.5
description: Processes for human oversight are defined, assessed, and documented in accordance with organizational
  policies from GOVERN function.
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
- map-3-5
- human-oversight
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
nist_id: MAP 3.5
ai_actors:
- Human Factors
- End-Users
- Domain Experts
- Operation and Monitoring
- AI Design
topics:
- Human oversight
---

# Summary

Processes for human oversight are defined, assessed, and documented in accordance with organizational policies from GOVERN function.

# Playbook About

As AI systems have evolved in accuracy and precision, computational systems have moved from being used purely for decision support—or for explicit use by and under the
control of a human operator—to automated decision making with limited input from humans. Computational decision support systems augment another, typically human, system in making decisions.These types of configurations increase the likelihood of outputs being produced with little human involvement. 

Defining and differentiating various human roles and responsibilities for AI systems’ governance,  and differentiating AI system overseers and those using or interacting with AI systems can enhance AI risk management activities. 

In critical systems, high-stakes settings, and systems deemed high-risk it is of vital importance to evaluate risks and effectiveness of oversight procedures before an AI system is deployed.

Ultimately, AI system oversight is a shared responsibility, and attempts to properly authorize or govern oversight practices will not be effective without organizational buy-in and accountability mechanisms, for example those suggested in the GOVERN function.

# Suggested Actions

- Identify and document AI systems’ features and capabilities that require human oversight, in relation to operational and societal contexts, trustworthy characteristics, and risks identified in MAP-1. 
- Establish practices for AI systems’ oversight in accordance with policies developed in GOVERN-1. 
- Define and develop training materials for relevant AI Actors about AI system performance, context of use, known limitations and negative impacts, and suggested warning labels.
- Include relevant AI Actors in AI system prototyping and testing activities. Conduct testing activities under scenarios similar to deployment conditions. 
- Evaluate AI system oversight practices for validity and reliability. When oversight practices undergo extensive updates or adaptations, retest, evaluate results, and course correct as necessary.
- Verify that model documents contain interpretable descriptions of system mechanisms, enabling oversight personnel to make informed, risk-based decisions about system risks.

# Documentation Prompts

### Organizations can document the following
- What are the roles, responsibilities, and delegation of authorities of personnel involved in the design, development, deployment, assessment and monitoring of the AI system?
- How does the entity assess whether personnel have the necessary skills, training, resources, and domain knowledge to fulfill their assigned responsibilities? 
- Are the relevant staff dealing with AI systems properly trained to interpret AI model output and decisions as well as to detect and manage bias in data?
- To what extent has the entity documented the AI system’s development, testing methodology, metrics, and performance outcomes?

### AI Transparency Resources
- GAO-21-519SP: AI Accountability Framework for Federal Agencies & Other Entities. [URL](https://www.gao.gov/products/gao-21-519sp)

# References

Ben Green, “The Flaws of Policies Requiring Human Oversight of Government Algorithms,” SSRN Journal, 2021. [URL](https://www.ssrn.com/abstract=3921216)

Luciano Cavalcante Siebert, Maria Luce Lupetti,  Evgeni Aizenberg, Niek Beckers, Arkady Zgonnikov, Herman Veluwenkamp, David Abbink, Elisa Giaccardi, Geert-Jan Houben, Catholijn Jonker, Jeroen van den Hoven, Deborah Forster, & Reginald Lagendijk (2021). Meaningful human control: actionable properties for AI system development. AI and Ethics. [URL](https://link.springer.com/article/10.1007/s43681-022-00167-3)

Mary Cummings, (2014). Automation and Accountability in Decision Support System Interface Design. The Journal of Technology Studies. 32. 10.21061/jots.v32i1.a.4. [URL](https://scholar.lib.vt.edu/ejournals/JOTS/v32/v32n1/pdf/cummings.pdf)

Madeleine Elish, M. (2016). Moral Crumple Zones: Cautionary Tales in Human-Robot Interaction (WeRobot 2016). SSRN Electronic Journal. 10.2139/ssrn.2757236. [URL](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2757236)

R Crootof, ME Kaminski, and WN Price II.  Humans in the Loop (March 25, 2022). Vanderbilt Law Review, Forthcoming 2023, U of Colorado Law Legal Studies Research Paper No. 22-10, U of Michigan Public Law Research Paper No. 22-011. [LINK](https://ssrn.com/abstract=4066781), [URL](http://dx.doi.org/10.2139/ssrn.4066781)

Bogdana Rakova, Jingying Yang, Henriette Cramer, & Rumman Chowdhury (2020). Where Responsible AI meets Reality. Proceedings of the ACM on Human-Computer Interaction, 5, 1 - 23. [URL](https://arxiv.org/pdf/2006.12358.pdf)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
