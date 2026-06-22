---
type: framework_subcategory
title: GOVERN 1.1
description: Legal and regulatory requirements involving AI are understood, managed, and documented.
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
- govern-1-1
- legal-and-regulatory
- governance
- ai-actor-training
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
nist_id: GOVERN 1.1
ai_actors:
- Governance and Oversight
topics:
- Legal and Regulatory
- Governance
- AI Actor Training
---

# Summary

Legal and regulatory requirements involving AI are understood, managed, and documented.

# Playbook About

AI systems may be subject to specific applicable legal and regulatory requirements. Some legal requirements can mandate (e.g., nondiscrimination, data privacy and security controls) documentation, disclosure, and increased AI system transparency. These requirements are complex and may not be applicable or differ across applications and contexts. 
 
For example, AI system testing processes for bias measurement, such as disparate impact, are not applied uniformly within the legal context. Disparate impact is broadly defined as a facially neutral policy or practice that disproportionately harms a group based on a protected trait. Notably, some modeling algorithms or debiasing techniques that rely on demographic information, could also come into tension with legal prohibitions on disparate treatment (i.e., intentional discrimination).

Additionally, some intended users of AI systems may not have consistent or reliable access to fundamental internet technologies (a phenomenon widely described as the “digital divide”) or may experience difficulties interacting with AI systems due to disabilities or impairments. Such factors may mean different communities experience bias or other negative impacts when trying to access AI systems. Failure to address such design issues may pose legal risks, for example in employment related activities affecting persons with disabilities.

# Suggested Actions

* Maintain awareness of the applicable legal and regulatory considerations and requirements specific to industry, sector, and business purpose, as well as the application context of the deployed AI system.
* Align risk management efforts with applicable legal standards.
* Maintain policies for training (and re-training) organizational staff about necessary legal or regulatory considerations that may impact AI-related design, development and deployment activities.

# Documentation Prompts

### Organizations can document the following
- To what extent has the entity defined and documented the regulatory environment—including minimum requirements in laws and regulations?
- Has the system been reviewed for its compliance to applicable laws, regulations, standards, and guidance? 
- To what extent has the entity defined and documented the regulatory environment—including applicable requirements in laws and regulations? 
- Has the system been reviewed for its compliance to relevant applicable laws, regulations, standards, and guidance? 

### AI Transparency Resources

GAO-21-519SP: AI Accountability Framework for Federal Agencies & Other Entities. [URL](https://www.gao.gov/products/gao-21-519sp)

# References

Andrew Smith, "Using Artificial Intelligence and Algorithms," FTC Business Blog (2020). [URL](https://www.ftc.gov/business-guidance/blog/2020/04/using-artificial-intelligence-and-algorithms)
 
Rebecca Kelly Slaughter, "Algorithms and Economic Justice," ISP Digital Future Whitepaper & YJoLT Special Publication (2021). [URL](https://law.yale.edu/sites/default/files/area/center/isp/documents/algorithms_and_economic_justice_master_final.pdf)
 
Patrick Hall, Benjamin Cox, Steven Dickerson, Arjun Ravi Kannan, Raghu Kulkarni, and Nicholas Schmidt, "A United States fair lending perspective on machine learning," Frontiers in Artificial Intelligence 4 (2021). [URL](https://www.frontiersin.org/articles/10.3389/frai.2021.695301/full)

AI Hiring Tools and the Law, Partnership on Employment & Accessible Technology (PEAT, peatworks.org). [URL](https://www.peatworks.org/ai-disability-inclusion-toolkit/ai-hiring-tools-and-the-law/)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
