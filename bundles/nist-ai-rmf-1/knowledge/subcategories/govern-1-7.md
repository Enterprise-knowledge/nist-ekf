---
type: framework_subcategory
title: GOVERN 1.7
description: Processes and procedures are in place for decommissioning and phasing out of AI systems safely and
  in a manner that does not increase risks or decrease the organization’s trustworthiness.
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
- govern-1-7
- decommission
- governance
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
- name: GOVERN-1
  path: /bundles/nist-ai-rmf-1/knowledge/categories/govern-1.md
  relation: part_of
  description: This Subcategory is part of AI RMF Category GOVERN-1.
nist_id: GOVERN 1.7
ai_actors:
- AI Deployment
- Operation and Monitoring
topics:
- Decommission
- Governance
---

# Summary

Processes and procedures are in place for decommissioning and phasing out of AI systems safely and in a manner that does not increase risks or decrease the organization’s trustworthiness.

# Playbook About

Irregular or indiscriminate termination or deletion of models or AI systems may be inappropriate and increase organizational risk. For example, AI systems may be subject to regulatory requirements or implicated in future security or legal investigations. To maintain trust, organizations may consider establishing policies and processes for the systematic and deliberate decommissioning of AI systems. Typically, such policies consider user and community concerns, risks in dependent and linked systems, and security, legal or regulatory concerns. Decommissioned models or systems may be stored in a model inventory along with active models,  for an established length  of time.

# Suggested Actions

- Establish policies for decommissioning AI systems. Such policies typically address:
    - User and community concerns, and reputational risks. 
    - Business continuity and financial risks.
    - Up and downstream system dependencies. 
    - Regulatory requirements (e.g., data retention). 
    - Potential future legal, regulatory, security or forensic investigations.
    - Migration to the replacement system, if appropriate.
- Establish policies that delineate where and for how long decommissioned systems, models and related artifacts are stored.
- Establish practices to track accountability and consider how decommission and other adaptations or changes in system deployment contribute to downstream impacts for individuals, groups and communities. 
- Establish policies that address ancillary data or artifacts that must be preserved for fulsome understanding or execution of the decommissioned AI system, e.g., predictions, explanations, intermediate input feature representations, usernames and passwords, etc.

# Documentation Prompts

### Organizations can document the following
- What processes exist for data generation, acquisition/collection, ingestion, staging/storage, transformations, security, maintenance, and dissemination?
- To what extent do these policies foster public trust and confidence in the use of the AI system?
- If anyone believes that the AI no longer meets this ethical framework, who will be responsible for receiving the concern and as appropriate investigating and remediating the issue? Do they have authority to modify, limit, or stop the use of the AI?
- If it relates to people, were there any ethical review applications/reviews/approvals? (e.g. Institutional Review Board applications)

### AI Transparency Resources
- GAO-21-519SP: AI Accountability Framework for Federal Agencies & Other Entities. [URL](https://www.gao.gov/products/gao-21-519sp)
- Intel.gov: AI Ethics Framework for Intelligence Community - 2020. [URL](https://www.intelligence.gov/artificial-intelligence-ethics-framework-for-the-intelligence-community)
- Datasheets for Datasets. [URL](http://arxiv.org/abs/1803.09010)

# References

Michelle De Mooy, Joseph Jerome and Vijay Kasschau, “Should It Stay or Should It Go? The Legal, Policy and Technical Landscape Around Data Deletion,” Center for Democracy and Technology, 2017. [URL](https://cdt.org/wp-content/uploads/2017/02/2017-02-23-Data-Deletion-FNL2.pdf)

Burcu Baykurt, "Algorithmic accountability in US cities: Transparency, impact, and political economy." Big Data & Society 9, no. 2 (2022): 20539517221115426. [URL](https://journals.sagepub.com/doi/full/10.1177/20539517221115426)

Upol Ehsan, Ranjit Singh, Jacob Metcalf and Mark O. Riedl. “The Algorithmic Imprint.” Proceedings of the 2022 ACM Conference on Fairness, Accountability, and Transparency (2022). [URL] (https://arxiv.org/pdf/2206.03275v1)

“Information System Decommissioning Guide,” Bureau of Land Management, 2011. [URL](https://www.blm.gov/sites/blm.gov/files/uploads/IM2011-174_att1.pdf)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
