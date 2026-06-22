---
type: framework_subcategory
title: MANAGE 2.3
description: Procedures are followed to respond to and recover from a previously unknown risk when it is identified.
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
- manage-2-3
- risk-response
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
- name: MANAGE-2
  path: /bundles/nist-ai-rmf-1/knowledge/categories/manage-2.md
  relation: part_of
  description: This Subcategory is part of AI RMF Category MANAGE-2.
nist_id: MANAGE 2.3
ai_actors:
- AI Deployment
- Operation and Monitoring
topics:
- Risk Response
---

# Summary

Procedures are followed to respond to and recover from a previously unknown risk when it is identified.

# Playbook About

AI systems – like any technology – can demonstrate non-functionality or failure or unexpected and unusual behavior. They also can be subject to attacks, incidents, or other misuse or abuse – which their sources are not always known apriori. Organizations can establish, document, communicate and maintain treatment procedures to recognize and counter, mitigate and manage risks that were not previously identified.

# Suggested Actions

- Protocols, resources, and metrics  are in place for continual monitoring of AI systems’ performance, trustworthiness, and alignment with contextual norms and values 
- Establish and regularly review treatment and response plans for incidents, negative impacts, or outcomes.
- Establish and maintain procedures to regularly monitor system components for drift, decontextualization, or other AI system behavior factors, 
- Establish and maintain procedures for capturing feedback about negative impacts.
- Verify contingency processes to handle any negative impacts associated with mission-critical AI systems, and to deactivate systems.
- Enable preventive and post-hoc exploration of AI system limitations by relevant AI actor groups.
- Decommission systems that exceed risk tolerances.

# Documentation Prompts

### Organizations can document the following

- Who will be responsible for maintaining, re-verifying, monitoring, and updating this AI once deployed?
- Are the responsibilities of the personnel involved in the various AI governance processes clearly defined? (Including responsibilities to decommission the AI system.)
- What processes exist for data generation, acquisition/collection, ingestion, staging/storage, transformations, security, maintenance, and dissemination?
- How will the appropriate performance metrics, such as accuracy, of the AI be monitored after the AI is deployed? 

### AI Transparency Resources

- Artificial Intelligence Ethics Framework For The Intelligence Community. [URL](https://www.intelligence.gov/artificial-intelligence-ethics-framework-for-the-intelligence-community) 
- WEF - Companion to the Model AI Governance Framework – Implementation and Self-Assessment Guide for Organizations. [URL](https://www.pdpc.gov.sg/-/media/files/pdpc/pdf-files/resource-for-organisation/ai/sgisago.ashx)
- GAO-21-519SP - Artificial Intelligence: An Accountability Framework for Federal Agencies & Other Entities. [URL](https://www.gao.gov/products/gao-21-519sp)

# References

AI Incident Database. 2022. AI Incident Database. [URL](https://incidentdatabase.ai/)

AIAAIC Repository. 2022. AI, algorithmic and automation incidents collected, dissected, examined, and divulged. [URL](https://www.aiaaic.org/aiaaic-repository)

Andrew Burt and Patrick Hall. 2018. What to Do When AI Fails. O’Reilly Media, Inc. (May 18, 2020). Retrieved October 17, 2022. [URL](https://www.oreilly.com/radar/what-to-do-when-ai-fails/)

National Institute for Standards and Technology (NIST). 2022. Cybersecurity Framework. [URL](https://www.nist.gov/cyberframework)

SANS Institute. 2022. Security Consensus Operational Readiness Evaluation (SCORE) Security Checklist [or Advanced Persistent Threat (APT) Handling Checklist]. [URL](https://www.sans.org/media/score/checklists/APT-IncidentHandling-Checklist.pdf)

Suchi Saria, Adarsh Subbaswamy. 2019. Tutorial: Safe and Reliable Machine Learning. arXiv:1904.07204. [URL](https://doi.org/10.48550/arXiv.1904.07204)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
