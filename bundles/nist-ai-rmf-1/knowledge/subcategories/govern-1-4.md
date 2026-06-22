---
type: framework_subcategory
title: GOVERN 1.4
description: The risk management process and its outcomes are established through transparent policies, procedures,
  and other controls based on organizational risk priorities.
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
- govern-1-4
- risk-management
- governance
- documentation
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
nist_id: GOVERN 1.4
ai_actors:
- Governance and Oversight
topics:
- Risk Management
- Governance
- Documentation
---

# Summary

The risk management process and its outcomes are established through transparent policies, procedures, and other controls based on organizational risk priorities.

# Playbook About

Clear policies and procedures relating to documentation and transparency facilitate and enhance efforts  to communicate roles and responsibilities for the Map, Measure and Manage functions across the AI lifecycle. Standardized documentation can help organizations systematically integrate AI risk management processes and enhance accountability efforts. For example, by adding their contact information to a work product document, AI actors can improve communication, increase ownership of work products, and potentially enhance consideration of product quality. Documentation may generate downstream benefits related to improved system replicability and robustness. Proper documentation storage and access procedures allow for quick retrieval of critical information during a negative incident. Explainable machine learning efforts (models and explanatory methods) may bolster technical documentation practices by introducing additional information for review and interpretation by AI Actors.

# Suggested Actions

- Establish and regularly review documentation policies that, among others, address information related to:
    - AI actors contact informations
    - Business justification
    - Scope and usages
    - Expected and potential risks and impacts
    - Assumptions and limitations
    - Description and characterization of training data
    - Algorithmic methodology
    - Evaluated alternative approaches
    - Description of output data
    - Testing and validation results (including explanatory visualizations and information)
    - Down- and up-stream dependencies
    - Plans for deployment, monitoring, and change management
    - Stakeholder engagement plans
- Verify documentation policies for AI systems are standardized across the organization and remain current.
- Establish policies for a model documentation inventory system and regularly review its completeness, usability, and efficacy.
- Establish mechanisms to regularly review the efficacy of risk management processes.
- Identify AI actors responsible for evaluating efficacy of risk management processes and approaches, and for course-correction based on results.
- Establish policies and processes regarding public disclosure of the use of AI and risk management material such as impact assessments, audits, model documentation and validation and testing results.
- Document and review the use and efficacy of different types of transparency tools and follow industry standards at the time a model is in use.

# Documentation Prompts

### Organizations can document the following
- To what extent has the entity clarified the roles, responsibilities, and delegated authorities to relevant stakeholders?
- What are the roles, responsibilities, and delegation of authorities of personnel involved in the design, development, deployment, assessment and monitoring of the AI system?
- How will the appropriate performance metrics, such as accuracy, of the AI be monitored after the AI is deployed? How much distributional shift or model drift from baseline performance is acceptable?

### AI Transparency Resources
- GAO-21-519SP: AI Accountability Framework for Federal Agencies & Other Entities. [URL](https://www.gao.gov/products/gao-21-519sp)
- Intel.gov: AI Ethics Framework for Intelligence Community  - 2020. [URL](https://www.intelligence.gov/artificial-intelligence-ethics-framework-for-the-intelligence-community)

# References

Bd. Governors Fed. Rsrv. Sys., Supervisory Guidance on Model Risk Management, SR Letter 11-7 (Apr. 4, 2011).

Off. Comptroller Currency, Comptroller’s Handbook: Model Risk Management (Aug. 2021). [URL](https://www.occ.gov/publications-and-resources/publications/comptrollers-handbook/files/model-risk-management/index-model-risk-management.html)

Margaret Mitchell et al., “Model Cards for Model Reporting.” Proceedings of 2019 FATML Conference. [URL](https://arxiv.org/pdf/1810.03993.pdf)

Timnit Gebru et al., “Datasheets for Datasets,” Communications of the ACM 64, No. 12, 2021. [URL](https://arxiv.org/pdf/1803.09010.pdf)

Emily M. Bender, Batya Friedman,  Angelina McMillan-Major (2022). A Guide for Writing Data Statements for Natural Language Processing. University of Washington. Accessed July 14, 2022. [URL](https://techpolicylab.uw.edu/wp-content/uploads/2021/11/Data_Statements_Guide_V2.pdf)

M. Arnold, R. K. E. Bellamy, M. Hind, et al. FactSheets: Increasing trust in AI services through supplier’s declarations of conformity. IBM Journal of Research and Development 63, 4/5 (July-September 2019), 6:1-6:13. [URL](https://techpolicylab.uw.edu/wp-content/uploads/2021/11/Data_Statements_Guide_V2.pdf)

Navdeep Gill, Abhishek Mathur, Marcos V. Conde (2022). A Brief Overview of AI Governance for Responsible Machine Learning Systems. ArXiv, abs/2211.13130. [URL](https://arxiv.org/pdf/2211.13130.pdf)

John Richards, David Piorkowski, Michael Hind, et al. A Human-Centered Methodology for Creating AI FactSheets. Bulletin of the IEEE Computer Society Technical Committee on Data Engineering. [URL](http://sites.computer.org/debull/A21dec/p47.pdf)

Christoph Molnar, Interpretable Machine Learning, lulu.com. [URL](https://christophm.github.io/interpretable-ml-book/)

David A. Broniatowski. 2021. Psychological Foundations of Explainability and Interpretability in Artificial Intelligence. National Institute of Standards and Technology (NIST) IR 8367. National Institute of Standards and Technology, Gaithersburg, MD. [URL](https://doi.org/10.6028/NIST.IR.8367)

OECD (2022), “OECD Framework for the Classification of AI systems”, OECD Digital Economy Papers, No. 323, OECD Publishing, Paris. [URL](https://doi.org/10.1787/cb6d9eca-en)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
