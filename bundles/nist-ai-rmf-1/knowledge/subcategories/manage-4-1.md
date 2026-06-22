---
type: framework_subcategory
title: MANAGE 4.1
description: Post-deployment AI system monitoring plans are implemented, including mechanisms for capturing and
  evaluating input from users and other relevant AI actors, appeal and override, decommissioning, incident response,
  recovery, and change management.
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
- manage-4-1
- monitoring
- participation
- ai-deployment
- ai-incidents
- risk-response
- adversarial
- risky-emergent-behavior
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
nist_id: MANAGE 4.1
ai_actors:
- AI Deployment
- Operation and Monitoring
- End-Users
- Human Factors
- Domain Experts
- Affected Individuals and Communities
topics:
- Monitoring
- Participation
- AI Deployment
- AI Incidents
- Risk Response
- Adversarial
- Risky Emergent Behavior
---

# Summary

Post-deployment AI system monitoring plans are implemented, including mechanisms for capturing and evaluating input from users and other relevant AI actors, appeal and override, decommissioning, incident response, recovery, and change management.

# Playbook About

AI system performance and trustworthiness can change due to a variety of factors. Regular AI system monitoring can help deployers identify performance degradations, adversarial attacks, unexpected and unusual behavior, near-misses, and impacts. Including pre- and post-deployment external feedback about AI system performance can enhance organizational awareness about positive and negative impacts, and reduce the time to respond to risks and harms.

# Suggested Actions

- Establish and maintain procedures to monitor AI system performance for risks and negative and positive impacts associated with trustworthiness characteristics. 
- Perform post-deployment TEVV tasks to evaluate AI system validity and reliability, bias and fairness, privacy, and security and resilience.
- Evaluate AI system trustworthiness in conditions similar to deployment context of use, and prior to deployment.
- Establish and implement red-teaming exercises at a prescribed cadence, and evaluate their efficacy. 
- Establish procedures for tracking dataset modifications such as data deletion or rectification requests.
- Establish mechanisms for regular communication and feedback between relevant AI actors and internal or external stakeholders to capture information about system performance, trustworthiness and impact.
- Share information about errors, near-misses, and attack patterns with incident databases, other organizations with similar systems, and system users and stakeholders.
- Respond to and document detected or reported negative impacts or issues in AI system performance and trustworthiness.
- Decommission systems that exceed establish risk tolerances.

# Documentation Prompts

### Organizations can document the following

- To what extent has the entity documented the post-deployment AI system’s testing methodology, metrics, and performance outcomes?
- How easily accessible and current is the information available to external stakeholders?

### AI Transparency Resources

- GAO-21-519SP - Artificial Intelligence: An Accountability Framework for Federal Agencies & Other Entities, [URL](https://www.gao.gov/products/gao-21-519sp)
- Datasheets for Datasets. [URL](https://arxiv.org/abs/1803.09010)

# References

Navdeep Gill, Patrick Hall, Kim Montgomery, and Nicholas Schmidt. "A Responsible Machine Learning Workflow with Focus on Interpretable Models, Post-hoc Explanation, and Discrimination Testing." Information 11, no. 3 (2020): 137. [URL](https://www.mdpi.com/2078-2489/11/3/137)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
