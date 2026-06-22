---
type: framework_subcategory
title: GOVERN 6.1
description: Policies and procedures are in place that address AI risks associated with third-party entities, including
  risks of infringement of a third party’s intellectual property or other rights.
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
- govern-6-1
- third-party
- legal-and-regulatory
- procurement
- supply-chain
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
- name: GOVERN-6
  path: /bundles/nist-ai-rmf-1/knowledge/categories/govern-6.md
  relation: part_of
  description: This Subcategory is part of AI RMF Category GOVERN-6.
nist_id: GOVERN 6.1
ai_actors:
- Third-party entities
- Operation and Monitoring
- Procurement
topics:
- Third-party
- Legal and Regulatory
- Procurement
- Supply Chain
- Governance
---

# Summary

Policies and procedures are in place that address AI risks associated with third-party entities, including risks of infringement of a third party’s intellectual property or other rights.

# Playbook About

Risk measurement and management can be complicated by how customers use or integrate third-party data or systems into AI products or services, particularly without sufficient internal governance structures and technical safeguards. 

Organizations usually engage multiple third parties for external expertise, data, software packages (both open source and commercial), and software and hardware platforms across the AI lifecycle. This engagement has beneficial uses and can increase complexities of risk management efforts.

Organizational approaches to managing third-party (positive and negative) risk may be tailored to the resources, risk profile, and use case for each system. Organizations can apply governance approaches to third-party AI systems and data as they would for internal resources — including open source software, publicly available data, and commercially available models.

# Suggested Actions

- Collaboratively establish policies that address third-party AI systems and data.
- Establish policies related to:
    - Transparency into third-party system functions, including knowledge about training data, training and inference algorithms, and assumptions and limitations.
    - Thorough testing of third-party AI systems. (See MEASURE for more detail)
    - Requirements for clear and complete instructions for third-party system usage.
- Evaluate policies for third-party technology. 
- Establish policies that address supply chain, full product lifecycle and associated processes, including legal, ethical, and other issues concerning procurement and use of third-party software or hardware systems and data.

# Documentation Prompts

### Organizations can document the following
- Did you establish mechanisms that facilitate the AI system’s auditability (e.g. traceability of the development process, the sourcing of training data and the logging of the AI system’s processes, outcomes, positive and negative impact)?
- If a third party created the AI, how will you ensure a level of explainability or interpretability?
- Did you ensure that the AI system can be audited by independent third parties?
- Did you establish a process for third parties (e.g. suppliers, end users, subjects, distributors/vendors or workers) to report potential vulnerabilities, risks or biases in the AI system?
- To what extent does the plan specifically address risks associated with acquisition, procurement of packaged software from vendors, cybersecurity controls, computational infrastructure, data, data science, deployment mechanics, and system failure?

### AI Transparency Resources
- GAO-21-519SP: AI Accountability Framework for Federal Agencies & Other Entities. [URL](https://www.gao.gov/products/gao-21-519sp)
- Intel.gov: AI Ethics Framework for Intelligence Community  - 2020. [URL](https://www.intelligence.gov/artificial-intelligence-ethics-framework-for-the-intelligence-community)
- WEF Model AI Governance Framework Assessment 2020. [URL](https://www.pdpc.gov.sg/-/media/Files/PDPC/PDF-Files/Resource-for-Organisation/AI/SGModelAIGovFramework2.pdf)
- WEF Companion to the Model AI Governance Framework- 2020. [URL](https://www.pdpc.gov.sg/-/media/Files/PDPC/PDF-Files/Resource-for-Organisation/AI/SGIsago.pdf)
- AI policies and initiatives, in Artificial Intelligence in Society, OECD, 2019. [URL](https://www.oecd.org/publications/artificial-intelligence-in-society-eedfee77-en.htm)
- Assessment List for Trustworthy AI (ALTAI) - The High-Level Expert Group on AI - 2019. [URL](https://digital-strategy.ec.europa.eu/en/library/assessment-list-trustworthy-artificial-intelligence-altai-self-assessment)

# References

Bd. Governors Fed. Rsrv. Sys., Supervisory Guidance on Model Risk Management, SR Letter 11-7 (Apr. 4, 2011)

“Proposed Interagency Guidance on Third-Party Relationships: Risk Management,” 2021. [URL](https://www.occ.gov/news-issuances/news-releases/2021/nr-occ-2021-74a.pdf)

Off. Comptroller Currency, Comptroller’s Handbook: Model Risk Management (Aug. 2021). [URL](https://www.occ.gov/publications-and-resources/publications/comptrollers-handbook/files/model-risk-management/index-model-risk-management.html)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
