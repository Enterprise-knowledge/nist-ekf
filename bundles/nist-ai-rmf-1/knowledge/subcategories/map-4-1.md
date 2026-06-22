---
type: framework_subcategory
title: MAP 4.1
description: Approaches for mapping AI technology and legal risks of its components – including the use of third-party
  data or software – are in place, followed, and documented, as are risks of infringement of a third-party’s intellectual
  property or other rights.
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
- map-4-1
- legal-and-regulatory
- third-party
- pre-trained-models
- supply-chain
- risk-tolerance
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
- name: MAP-4
  path: /bundles/nist-ai-rmf-1/knowledge/categories/map-4.md
  relation: part_of
  description: This Subcategory is part of AI RMF Category MAP-4.
nist_id: MAP 4.1
ai_actors:
- Third-party entities
- Procurement
- Operation and Monitoring
- Governance and Oversight
topics:
- Legal and Regulatory
- Third-party
- Pre-trained models
- Supply Chain
- Risk Tolerance
- Risky Emergent Behavior
---

# Summary

Approaches for mapping AI technology and legal risks of its components – including the use of third-party data or software – are in place, followed, and documented, as are risks of infringement of a third-party’s intellectual property or other rights.

# Playbook About

Technologies and personnel from third-parties are another potential sources of risk to consider during AI risk management activities. Such risks may be difficult to map since risk priorities or tolerances may not be the same as the deployer organization.

For example, the use of pre-trained models, which tend to rely on large uncurated dataset or often have undisclosed origins, has raised concerns about privacy, bias, and unanticipated effects along with possible introduction of increased levels of statistical uncertainty, difficulty with reproducibility, and issues with scientific validity.

# Suggested Actions

- Review audit reports, testing results, product roadmaps, warranties, terms of service, end user license agreements, contracts, and other documentation related to third-party entities to assist in value assessment and risk management activities.
- Review third-party software release schedules and software change management plans (hotfixes, patches, updates, forward- and backward- compatibility guarantees) for irregularities that may contribute to AI system risks.
- Inventory third-party material (hardware, open-source software, foundation models, open source data, proprietary software, proprietary data, etc.) required for system implementation and maintenance.
- Review redundancies related to third-party technology and personnel to assess potential risks due to lack of adequate support.

# Documentation Prompts

### Organizations can document the following
- Did you establish a process for third parties (e.g. suppliers, end users, subjects, distributors/vendors or workers) to report potential vulnerabilities, risks or biases in the AI system?
- If your organization obtained datasets from a third party, did your organization assess and manage the risks of using such datasets?
- How will the results be independently verified?

### AI Transparency Resources
- GAO-21-519SP: AI Accountability Framework for Federal Agencies & Other Entities. [URL](https://www.gao.gov/products/gao-21-519sp)
- Intel.gov: AI Ethics Framework for Intelligence Community  - 2020. [URL](https://www.intelligence.gov/artificial-intelligence-ethics-framework-for-the-intelligence-community)
- WEF Model AI Governance Framework Assessment 2020. [URL](https://www.pdpc.gov.sg/-/media/Files/PDPC/PDF-Files/Resource-for-Organisation/AI/SGModelAIGovFramework2.pdf)

# References

### Language  models

Emily M. Bender, Timnit Gebru, Angelina McMillan-Major, and Shmargaret Shmitchell. 2021. On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜. In Proceedings of the 2021 ACM Conference on Fairness, Accountability, and Transparency (FAccT '21). Association for Computing Machinery, New York, NY, USA, 610–623. [URL](https://doi.org/10.1145/3442188.3445922)

Julia Kreutzer, Isaac Caswell, Lisa Wang, et al. 2022. Quality at a Glance: An Audit of Web-Crawled Multilingual Datasets. Transactions of the Association for Computational Linguistics 10 (2022), 50–72.  [URL](https://doi.org/10.1162/tacl_a_00447)

Laura Weidinger, Jonathan Uesato, Maribeth Rauh, et al. 2022. Taxonomy of Risks posed by Language Models. In 2022 ACM Conference on Fairness, Accountability, and Transparency (FAccT '22). Association for Computing Machinery, New York, NY, USA, 214–229. [URL](https://doi.org/10.1145/3531146.3533088)

Office of the Comptroller of the Currency. 2021. Comptroller's Handbook: Model Risk Management, Version 1.0, August 2021. [URL](https://www.occ.gov/publications-and-resources/publications/comptrollers-handbook/files/model-risk-management/index-model-risk-management.html)

Rishi Bommasani, Drew A. Hudson, Ehsan Adeli, et al. 2021. On the Opportunities and Risks of Foundation Models. arXiv:2108.07258. [URL](https://arxiv.org/abs/2108.07258)

Jason Wei, Yi Tay, Rishi Bommasani, Colin Raffel, Barret Zoph, Sebastian Borgeaud, Dani Yogatama, Maarten Bosma, Denny Zhou, Donald Metzler, Ed H. Chi, Tatsunori Hashimoto, Oriol Vinyals, Percy Liang, Jeff Dean, William Fedus. “Emergent Abilities of Large Language Models.” ArXiv abs/2206.07682 (2022). [URL](https://arxiv.org/pdf/2206.07682.pdf)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
