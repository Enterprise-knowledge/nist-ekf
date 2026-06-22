---
type: framework_subcategory
title: GOVERN 1.3
description: Processes and procedures are in place to determine the needed level of risk management activities based
  on the organization's risk tolerance.
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
- govern-1-3
- risk-tolerance
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
nist_id: GOVERN 1.3
ai_actors:
- Governance and Oversight
topics:
- Risk Tolerance
- Governance
---

# Summary

Processes and procedures are in place to determine the needed level of risk management activities based on the organization's risk tolerance.

# Playbook About

Risk management resources are finite in any organization. Adequate AI governance policies delineate the mapping, measurement, and prioritization of risks to allocate resources toward the most material issues for an AI system to ensure effective risk management. Policies may specify systematic processes for assigning mapped and measured risks to standardized risk scales. 

AI risk tolerances  range from negligible to critical – from, respectively, almost no risk to risks that can result in irredeemable human, reputational, financial, or environmental losses. Risk tolerance rating policies consider different sources of risk, (e.g., financial, operational, safety and wellbeing, business, reputational, or model risks). A typical risk measurement approach entails the multiplication, or qualitative combination, of measured or estimated impact and likelihood of impacts into a risk score (risk ≈ impact x likelihood). This score is then placed on a risk scale. Scales for risk may be qualitative, such as red-amber-green (RAG), or may entail simulations or econometric approaches. Impact assessments are a common tool for understanding the severity of mapped risks. In the most fulsome AI risk management approaches, all models are assigned to a risk level.

# Suggested Actions

- Establish policies to define mechanisms for measuring or understanding an AI system’s potential impacts, e.g., via regular impact assessments at key stages in the AI lifecycle, connected to system impacts and frequency of system updates.
- Establish policies to define mechanisms for measuring or understanding the likelihood of an AI system’s impacts and their magnitude at key stages in the AI lifecycle. 
- Establish policies that define assessment scales for measuring potential AI system impact. Scales may be qualitative, such as red-amber-green (RAG), or may entail simulations or econometric approaches. 
- Establish policies for assigning an overall risk measurement approach for an AI system, or its important components, e.g., via multiplication or combination of a mapped risk’s impact and likelihood (risk ≈ impact x likelihood).
- Establish policies to assign systems to uniform risk scales that are valid across the organization’s AI portfolio (e.g. documentation templates), and acknowledge risk tolerance and risk levels may change over the lifecycle of an AI system.

# Documentation Prompts

### Organizations can document the following
- How do system performance metrics inform risk tolerance decisions?
- What policies has the entity developed to ensure the use of the AI system is consistent with organizational risk tolerance?
- How do the entity’s data security and privacy assessments inform risk tolerance decisions?


### AI Transparency Resources
- GAO-21-519SP: AI Accountability Framework for Federal Agencies & Other Entities. [URL](https://www.gao.gov/products/gao-21-519sp)

# References

Board of Governors of the Federal Reserve System. SR 11-7: Guidance on Model Risk Management. (April 4, 2011). [URL](https://www.federalreserve.gov/supervisionreg/srletters/sr1107.htm)

The Office of the Comptroller of the Currency. Enterprise Risk Appetite Statement. (Nov. 20, 2019). [URL](https://www.occ.treas.gov/publications-and-resources/publications/banker-education/files/pub-risk-appetite-statement.pdf)

Brenda Boultwood, How to Develop an Enterprise Risk-Rating Approach (Aug. 26, 2021). Global Association of Risk Professionals (garp.org). Accessed Jan. 4, 2023. [URL](https://www.garp.org/risk-intelligence/culture-governance/how-to-develop-an-enterprise-risk-rating-approach)

GAO-17-63: Enterprise Risk Management: Selected Agencies’ Experiences Illustrate Good Practices in Managing Risk. [URL](https://www.gao.gov/assets/gao-17-63.pdf)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
