---
type: framework_subcategory
title: MEASURE 3.2
description: Risk tracking approaches are considered for settings where AI risks are difficult to assess using currently
  available measurement techniques or where metrics are not yet available.
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
- measure-3-2
- monitoring
- continual-improvement
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
- name: MEASURE-3
  path: /bundles/nist-ai-rmf-1/knowledge/categories/measure-3.md
  relation: part_of
  description: This Subcategory is part of AI RMF Category MEASURE-3.
nist_id: MEASURE 3.2
ai_actors:
- TEVV
- Domain Experts
- AI Impact Assessment
- Operation and Monitoring
topics:
- Monitoring
- Continual Improvement
---

# Summary

Risk tracking approaches are considered for settings where AI risks are difficult to assess using currently available measurement techniques or where metrics are not yet available.

# Playbook About

Risks identified in the Map function may be complex, emerge over time, or difficult to measure. Systematic methods for risk tracking, including novel measurement approaches, can be established as part of regular monitoring and improvement processes.

# Suggested Actions

- Establish processes for tracking emergent risks that may not be measurable with current approaches. Some processes may include:
	- Recourse mechanisms for faulty AI system outputs.
	- Bug bounties.
	- Human-centered design approaches.
	- User-interaction and experience research.
	- Participatory stakeholder engagement with affected or potentially impacted individuals and communities.
- Identify AI actors responsible for tracking emergent risks and inventory methods. 
- Determine and document the rate of occurrence and severity level for complex or difficult-to-measure risks when:
	- Prioritizing new measurement approaches for deployment tasks. 
	- Allocating AI system risk management resources.
	- Evaluating AI system improvements.
	- Making go/no-go decisions for subsequent system iterations.

# Documentation Prompts

### Organizations can document the following

- Who is ultimately responsible for the decisions of the AI and is this person aware of the intended uses and limitations of the analytic?
- Who will be responsible for maintaining, re-verifying, monitoring, and updating this AI once deployed?
- To what extent does the entity communicate its AI strategic goals and objectives to the community of stakeholders?
- Given the purpose of this AI, what is an appropriate interval for checking whether it is still accurate, unbiased, explainable, etc.? What are the checks for this model?
- If anyone believes that the AI no longer meets this ethical framework, who will be responsible for receiving the concern and as appropriate investigating and remediating the issue? Do they have authority to modify, limit, or stop the use of the AI?

### AI Transparency Resources

- GAO-21-519SP - Artificial Intelligence: An Accountability Framework for Federal Agencies & Other Entities. [URL](https://www.gao.gov/products/gao-21-519sp)
- Artificial Intelligence Ethics Framework For The Intelligence Community. [URL](https://www.intelligence.gov/artificial-intelligence-ethics-framework-for-the-intelligence-community)

# References

ISO. "ISO 9241-210:2019 Ergonomics of human-system interaction — Part 210: Human-centred design for interactive systems." 2nd ed. ISO Standards, July 2019. [URL](https://www.iso.org/standard/77520.html)

Mark C. Paulk, Bill Curtis, Mary Beth Chrissis, and Charles V. Weber. “Capability Maturity Model, Version 1.1.” IEEE Software 10, no. 4 (1993): 18–27. [URL](https://doi.org/10.1109/52.219617. Note: Copy available via the University of Arizona at https://uweb.engr.arizona.edu/~ece473/readings/22-Capability%20MAturity%20Model.pdf)

Jeff Patton, Peter Economy, Martin Fowler, Alan Cooper, and Marty Cagan. User Story Mapping: Discover the Whole Story, Build the Right Product. O'Reilly, 2014. [URL](https://www.oreilly.com/library/view/user-story-mapping/9781491904893/)

Rumman Chowdhury and Jutta Williams. "Introducing Twitter’s first algorithmic bias bounty challenge." Twitter Engineering Blog, July 30, 2021. [URL](https://blog.twitter.com/engineering/en_us/topics/insights/2021/algorithmic-bias-bounty-challenge)

HackerOne. "Twitter Algorithmic Bias." HackerOne, August 8, 2021. [URL](https://hackerone.com/twitter-algorithmic-bias?type=team)

Josh Kenway, Camille François, Sasha Costanza-Chock, Inioluwa Deborah Raji, and Joy Buolamwini. "Bug Bounties for Algorithmic Harms?" Algorithmic Justice League, January 2022. [URL](https://www.ajl.org/bugs)

Microsoft. “Community Jury.” Microsoft Learn's Azure Application Architecture Guide, 2023. [URL](https://learn.microsoft.com/en-us/azure/architecture/guide/responsible-innovation/community-jury/)

Margarita Boyarskaya, Alexandra Olteanu, and Kate Crawford. "Overcoming Failures of Imagination in AI Infused System Development and Deployment." arXiv preprint, submitted December 10, 2020. [URL](https://arxiv.org/abs/2011.13416)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
