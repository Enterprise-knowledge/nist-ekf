---
type: framework_subcategory
title: GOVERN 4.2
description: Organizational teams document the risks and potential impacts of the AI technology they design, develop,
  deploy, evaluate and use, and communicate about the impacts more broadly.
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
- govern-4-2
- risk-culture
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
- name: GOVERN-4
  path: /bundles/nist-ai-rmf-1/knowledge/categories/govern-4.md
  relation: part_of
  description: This Subcategory is part of AI RMF Category GOVERN-4.
nist_id: GOVERN 4.2
ai_actors:
- AI Design
- AI Development
- AI Deployment
- Operation and Monitoring
topics:
- Risk Culture
- Governance
- Impact Assessment
---

# Summary

Organizational teams document the risks and potential impacts of the AI technology they design, develop, deploy, evaluate and use, and communicate about the impacts more broadly.

# Playbook About

Impact assessments are one approach for driving responsible technology development practices. And, within a specific use case, these assessments can provide a high-level structure for organizations to frame risks of a given algorithm or deployment. Impact assessments can also serve as a mechanism for organizations to articulate risks and generate documentation for managing and oversight activities when harms do arise.

Impact assessments may:

- be applied at the beginning of a process but also iteratively and regularly since goals and outcomes can evolve over time. 
- include perspectives from AI actors, including operators, users, and potentially impacted communities (including historically marginalized communities, those with disabilities, and individuals impacted by the digital divide), 
- assist in “go/no-go” decisions for an AI system. 
- consider conflicts of interest, or undue influence, related to the organizational team being assessed.

See the MAP function playbook guidance for more information relating to impact assessments.

# Suggested Actions

- Establish impact assessment policies and processes for AI systems used by the organization.
- Align organizational impact assessment activities with relevant regulatory or legal requirements. 
- Verify that impact assessment activities are appropriate to evaluate the potential negative impact of a system and how quickly a system changes, and that assessments are applied on a regular basis.
- Utilize impact assessments to inform broader evaluations of AI system risk.

# Documentation Prompts

### Organizations can document the following
- How has the entity identified and mitigated potential impacts of bias in the data, including inequitable or discriminatory outcomes?
- How has the entity documented the AI system’s data provenance, including sources, origins, transformations, augmentations, labels, dependencies, constraints, and metadata?
- To what extent has the entity clearly defined technical specifications and requirements for the AI system?
- To what extent has the entity documented and communicated the AI system’s development, testing methodology, metrics, and performance outcomes?
- Have you documented and explained that machine errors may differ from human errors?

### AI Transparency Resources
- GAO-21-519SP: AI Accountability Framework for Federal Agencies & Other Entities. [URL](https://www.gao.gov/products/gao-21-519sp)
- Datasheets for Datasets. [URL](http://arxiv.org/abs/1803.09010)

# References

Dillon Reisman, Jason Schultz, Kate Crawford, Meredith Whittaker, “Algorithmic Impact Assessments: A Practical Framework For Public Agency Accountability,” AI Now Institute, 2018. [URL](https://ainowinstitute.org/aiareport2018.pdf)

H.R. 2231, 116th Cong. (2019). [URL](https://www.congress.gov/bill/116th-congress/house-bill/2231/text)

BSA The Software Alliance (2021) Confronting Bias: BSA’s Framework to Build Trust in AI. [URL](https://www.bsa.org/reports/confronting-bias-bsas-framework-to-build-trust-in-ai)

Anthony M. Barrett, Dan Hendrycks, Jessica Newman and Brandie Nonnecke. Actionable Guidance for High-Consequence AI Risk Management: Towards Standards Addressing AI Catastrophic Risks. ArXiv abs/2206.08966 (2022) https://arxiv.org/abs/2206.08966

David Wright, “Making Privacy Impact Assessments More Effective." The Information Society 29, 2013. [URL](https://iapp.org/media/pdf/knowledge_center/Making_PIA__more_effective.pdf)

Konstantinia Charitoudi and Andrew Blyth. A Socio-Technical Approach to Cyber Risk Management and Impact Assessment. Journal of Information Security 4, 1 (2013), 33-41. [URL](https://www.scirp.org/pdf/JIS_2013013014352043.pdf)

Emanuel Moss, Elizabeth Anne Watkins, Ranjit Singh, Madeleine Clare Elish, & Jacob Metcalf. 2021. “Assembling Accountability: Algorithmic Impact Assessment for the Public Interest”. [URL](https://datasociety.net/library/assembling-accountability-algorithmic-impact-assessment-for-the-public-interest/)

Microsoft. Responsible AI Impact Assessment Template. 2022. [URL](https://blogs.microsoft.com/wp-content/uploads/prod/sites/5/2022/06/Microsoft-RAI-Impact-Assessment-Template.pdf)

Microsoft. Responsible AI Impact Assessment Guide. 2022. [URL](https://blogs.microsoft.com/wp-content/uploads/prod/sites/5/2022/06/Microsoft-RAI-Impact-Assessment-Guide.pdf)

Microsoft. Foundations of assessing harm. 2022.

Mauritz Kop, “AI Impact Assessment & Code of Conduct,” Futurium, May 2019. [URL](https://futurium.ec.europa.eu/en/european-ai-alliance/best-practices/ai-impact-assessment-code-conduct)

Dillon Reisman, Jason Schultz, Kate Crawford, and Meredith Whittaker, “Algorithmic Impact Assessments: A Practical Framework For Public Agency Accountability,” AI Now, Apr. 2018. [URL](https://ainowinstitute.org/aiareport2018.pdf)

Andrew D. Selbst, “An Institutional View Of Algorithmic Impact Assessments,” Harvard Journal of Law & Technology, vol. 35, no. 1, 2021

Ada Lovelace Institute. 2022. Algorithmic Impact Assessment: A Case Study in Healthcare. Accessed July 14, 2022. [URL](https://www.adalovelaceinstitute.org/report/algorithmic-impact-assessment-case-study-healthcare/)

Kathy Baxter, AI Ethics Maturity Model, Salesforce [URL](https://www.salesforceairesearch.com/static/ethics/EthicalAIMaturityModel.pdf)

Ravit Dotan, Borhane Blili-Hamelin, Ravi Madhavan, Jeanna Matthews, Joshua Scarpino, & Carol Anderson. (2024). A Flexible Maturity Model for AI Governance Based on the NIST AI Risk Management Framework [Technical Report]. IEEE. [URL](https://ieeeusa.org/product/a-flexible-maturity-model-for-ai-governance)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
