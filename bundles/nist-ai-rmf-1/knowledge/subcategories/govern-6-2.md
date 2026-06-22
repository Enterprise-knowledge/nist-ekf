---
type: framework_subcategory
title: GOVERN 6.2
description: Contingency processes are in place to handle failures or incidents in third-party data or AI systems
  deemed to be high-risk.
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
- govern-6-2
- third-party
- governance
- risk-management
- supply-chain
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
- name: GOVERN-6
  path: /bundles/nist-ai-rmf-1/knowledge/categories/govern-6.md
  relation: part_of
  description: This Subcategory is part of AI RMF Category GOVERN-6.
nist_id: GOVERN 6.2
ai_actors:
- AI Deployment
- TEVV
- Operation and Monitoring
- Third-party entities
topics:
- Third-party
- Governance
- Risk Management
- Supply Chain
---

# Summary

Contingency processes are in place to handle failures or incidents in third-party data or AI systems deemed to be high-risk.

# Playbook About

To mitigate the potential harms of third-party system failures, organizations may implement policies and procedures that include redundancies for covering third-party functions.

# Suggested Actions

- Establish policies for handling third-party system failures to include consideration of redundancy mechanisms for vital third-party AI systems.
- Verify that incident response plans address third-party AI systems.

# Documentation Prompts

### Organizations can document the following
- To what extent does the plan specifically address risks associated with acquisition, procurement of packaged software from vendors, cybersecurity controls, computational infrastructure, data, data science, deployment mechanics, and system failure?
- Did you establish a process for third parties (e.g. suppliers, end users, subjects, distributors/vendors or workers) to report potential vulnerabilities, risks or biases in the AI system?
- If your organization obtained datasets from a third party, did your organization assess and manage the risks of using such datasets?

### AI Transparency Resources
- GAO-21-519SP: AI Accountability Framework for Federal Agencies & Other Entities. [URL](https://www.gao.gov/products/gao-21-519sp)
- WEF Model AI Governance Framework Assessment 2020. [URL](https://www.pdpc.gov.sg/-/media/Files/PDPC/PDF-Files/Resource-for-Organisation/AI/SGModelAIGovFramework2.pdf)
- WEF Companion to the Model AI Governance Framework- 2020. [URL](https://www.pdpc.gov.sg/-/media/Files/PDPC/PDF-Files/Resource-for-Organisation/AI/SGIsago.pdf)
- AI policies and initiatives, in Artificial Intelligence in Society, OECD, 2019. [URL](https://www.oecd.org/publications/artificial-intelligence-in-society-eedfee77-en.htm)

# References

Bd. Governors Fed. Rsrv. Sys., Supervisory Guidance on Model Risk Management, SR Letter 11-7 (Apr. 4, 2011)

“Proposed Interagency Guidance on Third-Party Relationships: Risk Management,” 2021. [URL](https://www.occ.gov/news-issuances/news-releases/2021/nr-occ-2021-74a.pdf)

Off. Comptroller Currency, Comptroller’s Handbook: Model Risk Management (Aug. 2021). [URL](https://www.occ.gov/publications-and-resources/publications/comptrollers-handbook/files/model-risk-management/index-model-risk-management.html)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
