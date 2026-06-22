---
type: framework_subcategory
title: GOVERN 5.1
description: Organizational policies and practices are in place to collect, consider, prioritize, and integrate
  feedback from those external to the team that developed or deployed the AI system regarding the potential individual
  and societal impacts related to AI risks.
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
- govern-5-1
- participation
- governance
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
- name: GOVERN-5
  path: /bundles/nist-ai-rmf-1/knowledge/categories/govern-5.md
  relation: part_of
  description: This Subcategory is part of AI RMF Category GOVERN-5.
nist_id: GOVERN 5.1
ai_actors:
- AI Design
- Governance and Oversight
- AI Impact Assessment
- Affected Individuals and Communities
topics:
- Participation
- Governance
- Impact Assessment
---

# Summary

Organizational policies and practices are in place to collect, consider, prioritize, and integrate feedback from those external to the team that developed or deployed the AI system regarding the potential individual and societal impacts related to AI risks.

# Playbook About

Beyond internal and laboratory-based system testing, organizational policies and practices may consider AI system fitness-for-purpose related to the intended context of use.

Participatory stakeholder engagement is one type of qualitative activity to help AI actors answer questions such as whether to pursue a project or how to design with impact in mind. This type of feedback, with domain expert input, can also assist AI actors to identify emergent scenarios and risks in certain AI applications. The consideration of when and how to convene a group and the kinds of individuals, groups, or community organizations to include is an iterative process connected to the system's purpose and its level of risk. Other factors relate to how to collaboratively and respectfully capture stakeholder feedback and insight that is useful, without being a solely perfunctory exercise.

These activities are best carried out by personnel with expertise in participatory practices, qualitative methods, and translation of contextual feedback for technical audiences.

Participatory engagement is not a one-time exercise and is best carried out from the very beginning of AI system commissioning through the end of the lifecycle. Organizations can consider how to incorporate engagement when beginning a project and as part of their monitoring of systems. Engagement is often utilized as a consultative practice, but this perspective may inadvertently lead to “participation washing.” Organizational transparency about the purpose and goal of the engagement can help mitigate that possibility.

Organizations may also consider targeted consultation with subject matter experts as a complement to participatory findings. Experts may assist internal staff in identifying and conceptualizing potential negative impacts that were previously not considered.

# Suggested Actions

- Establish AI risk management policies that explicitly address mechanisms for collecting, evaluating, and incorporating stakeholder and user feedback that could include:
    - Recourse mechanisms for faulty AI system outputs.
    - Bug bounties.
    - Human-centered design.
    - User-interaction and experience research.
    - Participatory stakeholder engagement with individuals and communities that may experience negative impacts.
- Verify that stakeholder feedback is considered and addressed, including environmental concerns, and across the entire population of intended users, including historically excluded populations, people with disabilities, older people, and those with limited access to the internet and other basic technologies.
- Clarify the organization’s principles as they apply to AI systems – considering those which have been proposed publicly – to inform external stakeholders of the organization’s values. Consider publishing or adopting AI principles.

# Documentation Prompts

### Organizations can document the following 
- What type of information is accessible on the design, operations, and limitations of the AI system to external stakeholders, including end users, consumers, regulators, and individuals impacted by use of the AI system?
- To what extent has the entity clarified the roles, responsibilities, and delegated authorities to relevant stakeholders?
- How easily accessible and current is the information available to external stakeholders?
- What was done to mitigate or reduce the potential for harm?
- Stakeholder involvement: Include diverse perspectives from a community of stakeholders throughout the AI life cycle to mitigate risks.

### AI Transparency Resources
- Datasheets for Datasets. [URL](http://arxiv.org/abs/1803.09010)
- GAO-21-519SP: AI Accountability Framework for Federal Agencies & Other Entities. [URL](https://www.gao.gov/products/gao-21-519sp)
- AI policies and initiatives, in Artificial Intelligence in Society, OECD, 2019. [URL](https://www.oecd.org/publications/artificial-intelligence-in-society-eedfee77-en.htm)
- Stakeholders in Explainable AI, Sep. 2018. [URL](http://arxiv.org/abs/1810.00184)

# References

ISO, “Ergonomics of human-system interaction — Part 210: Human-centered design for interactive systems,” ISO 9241-210:2019 (2nd ed.), July 2019. [URL](https://www.iso.org/standard/77520.html)

Rumman Chowdhury and Jutta Williams, "Introducing Twitter’s first algorithmic bias bounty challenge," [URL](https://blog.twitter.com/engineering/en_us/topics/insights/2021/algorithmic-bias-bounty-challenge)

Leonard Haas and Sebastian Gießler, “In the realm of paper tigers – exploring the failings of AI ethics guidelines,” AlgorithmWatch, 2020. [URL](https://algorithmwatch.org/en/ai-ethics-guidelines-inventory-upgrade-2020/)

Josh Kenway, Camille Francois, Dr. Sasha Costanza-Chock, Inioluwa Deborah Raji, & Dr. Joy Buolamwini. 2022. Bug Bounties for Algorithmic Harms? Algorithmic Justice League. Accessed July 14, 2022. [URL](https://www.ajl.org/bugs)

Microsoft Community Jury , Azure Application Architecture Guide. [URL](https://docs.microsoft.com/en-us/azure/architecture/guide/responsible-innovation/community-jury/)

“Definition of independent verification and validation (IV&V)”, in IEEE 1012, IEEE Standard for System, Software, and Hardware Verification and Validation. Annex C, [URL](https://people.eecs.ku.edu/~hossein/Teaching/Stds/1012.pdf)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
