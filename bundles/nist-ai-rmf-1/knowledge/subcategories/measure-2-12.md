---
type: framework_subcategory
title: MEASURE 2.12
description: Environmental impact and sustainability of AI model training and management activities – as identified
  in the MAP function – are assessed and documented.
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
- measure-2-12
- tevv
- environmental-impact
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
- name: MEASURE-2
  path: /bundles/nist-ai-rmf-1/knowledge/categories/measure-2.md
  relation: part_of
  description: This Subcategory is part of AI RMF Category MEASURE-2.
nist_id: MEASURE 2.12
ai_actors:
- TEVV
- Domain Experts
- Operation and Monitoring
- AI Impact Assessment
- AI Deployment
topics:
- TEVV
- Environmental Impact
---

# Summary

Environmental impact and sustainability of AI model training and management activities – as identified in the MAP function – are assessed and documented.

# Playbook About

Large-scale, high-performance computational resources used by AI systems for training and operation can contribute to environmental impacts.  Direct negative impacts to the environment from these processes are related to energy consumption, water consumption, and greenhouse gas (GHG) emissions. The OECD has identified metrics for each type of negative direct impact. 

Indirect negative impacts to the environment reflect the complexity of interactions between human behavior, socio-economic systems, and the environment and can include induced consumption and “rebound effects”, where efficiency gains are offset by accelerated resource consumption. 

Other AI related environmental impacts can arise from the production of computational equipment and networks (e.g. mining and extraction of raw materials), transporting hardware, and electronic waste recycling or disposal.

# Suggested Actions

- Include environmental impact indicators in AI system design and development plans, including reducing consumption and improving efficiencies.
- Identify and implement key indicators of AI system energy and water consumption and efficiency, and/or GHG emissions. 
- Establish measurable baselines for sustainable AI system operation in accordance with organizational policies, regulatory compliance, legal frameworks, and environmental protection and sustainability norms.
- Assess tradeoffs between AI system performance and sustainable operations in accordance with organizational principles and policies, regulatory compliance, legal frameworks, and environmental protection and sustainability norms.
- Identify and establish acceptable resource consumption and efficiency, and GHG emissions levels, along with actions to be taken if indicators rise above acceptable levels.
- Estimate AI system emissions levels throughout the AI lifecycle via carbon calculators or similar process.

# Documentation Prompts

### Organizations can document the following

- Are greenhouse gas emissions, and energy and water consumption and efficiency tracked within the organization?
- Are deployed AI systems evaluated for potential upstream and downstream environmental impacts (e.g., increased consumption, increased emissions, etc.)?
- Could deployed AI systems cause environmental incidents, e.g., air or water pollution incidents, toxic spills, fires or explosions?


### AI Transparency Resources

- GAO-21-519SP - Artificial Intelligence: An Accountability Framework for Federal Agencies & Other Entities. [URL](https://www.gao.gov/products/gao-21-519sp)
- Artificial Intelligence Ethics Framework For The Intelligence Community. [URL](https://www.intelligence.gov/artificial-intelligence-ethics-framework-for-the-intelligence-community) 
- Datasheets for Datasets. [URL](https://arxiv.org/abs/1803.09010)

# References

Organisation for Economic Co-operation and Development (OECD). "Measuring the environmental impacts of artificial intelligence compute and applications: The AI footprint.” OECD Digital Economy Papers, No. 341, OECD Publishing, Paris. [URL](https://doi.org/10.1787/7babf571-en)

Victor Schmidt, Alexandra Luccioni, Alexandre Lacoste, and Thomas Dandres. “Machine Learning CO2 Impact Calculator.” ML CO2 Impact, n.d. [URL](https://mlco2.github.io/impact/)

Alexandre Lacoste, Alexandra Luccioni, Victor Schmidt, and Thomas Dandres. "Quantifying the Carbon Emissions of Machine Learning." arXiv preprint, submitted November 4, 2019. [URL](https://arxiv.org/abs/1910.09700)

Matthew Hutson. “Measuring AI’s Carbon Footprint: New Tools Track and Reduce Emissions from Machine Learning.” IEEE Spectrum, November 22, 2022. [URL](https://spectrum.ieee.org/ai-carbon-footprint)

Association for Computing Machinery (ACM). "TechBriefs: Computing and Climate Change." ACM Technology Policy Council, November 2021. [URL](https://dl.acm.org/doi/pdf/10.1145/3483410)

Roy Schwartz, Jesse Dodge, Noah A. Smith, and Oren Etzioni. “Green AI.” Communications of the ACM 63, no. 12 (December 2020): 54–63. [URL](https://doi.org/10.1145/3381831)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
