---
type: framework_subcategory
title: MEASURE 2.3
description: AI system performance or assurance criteria are measured qualitatively or quantitatively and demonstrated
  for conditions similar to deployment setting(s). Measures are documented.
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
- measure-2-3
- tevv
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
- name: MEASURE-2
  path: /bundles/nist-ai-rmf-1/knowledge/categories/measure-2.md
  relation: part_of
  description: This Subcategory is part of AI RMF Category MEASURE-2.
nist_id: MEASURE 2.3
ai_actors:
- TEVV
- AI Deployment
topics:
- TEVV
- Impact Assessment
---

# Summary

AI system performance or assurance criteria are measured qualitatively or quantitatively and demonstrated for conditions similar to deployment setting(s). Measures are documented.

# Playbook About

The current risk and impact environment suggests AI system performance estimates are insufficient and require a deeper understanding of deployment context of use. Computationally focused performance testing and evaluation schemes are restricted to test data sets and in silico techniques. These approaches do not directly evaluate risks and impacts in real world environments and can only predict what might create impact based on an approximation of expected AI use. To properly manage risks, more direct information is necessary to understand how and under what conditions deployed AI creates impacts, who is most likely to be impacted, and what that experience is like.

# Suggested Actions

- Conduct regular and sustained engagement with potentially impacted communities 
- Maintain a demographically diverse and multidisciplinary and collaborative internal team
- Regularly test and evaluate systems in non-optimized conditions, and in collaboration with AI actors in user interaction and user experience (UI/UX) roles. 
- Evaluate feedback from stakeholder engagement activities, in collaboration with human factors and socio-technical experts.
- Collaborate with socio-technical, human factors, and UI/UX experts to identify notable characteristics in context of use that can be translated into system testing scenarios.
- Measure AI systems prior to deployment in conditions similar to expected scenarios. 
- Measure and document performance criteria such as validity (false positive rate, false negative rate, etc.) and efficiency (training times, prediction latency, etc.) related to ground truth within the deployment context of use.
- Measure assurance criteria such as AI actor competency and experience. 
- Document differences between measurement setting and the deployment environment(s).

# Documentation Prompts

### Organizations can document the following

- What experiments were initially run on this dataset? To what extent have experiments on the AI system been documented?
- To what extent does the system/entity consistently measure progress towards stated goals and objectives?
- How will the appropriate performance metrics, such as accuracy, of the AI be monitored after the AI is deployed? How much distributional shift or model drift from baseline performance is acceptable?
- As time passes and conditions change, is the training data still representative of the operational environment?
- What testing, if any, has the entity conducted on theAI system to identify errors and limitations (i.e.adversarial or stress testing)?

### AI Transparency Resources

- Artificial Intelligence Ethics Framework For The Intelligence Community. [URL](https://www.intelligence.gov/artificial-intelligence-ethics-framework-for-the-intelligence-community) 
- WEF Companion to the Model AI Governance Framework- WEF - Companion to the Model AI Governance Framework, 2020. [URL](https://www.pdpc.gov.sg/-/media/Files/PDPC/PDF-Files/Resource-for-Organisation/AI/SGIsago.pdf)
- Datasheets for Datasets. [URL](https://arxiv.org/abs/1803.09010)

# References

Trevor Hastie, Robert Tibshirani, and Jerome Friedman. The Elements of Statistical Learning: Data Mining, Inference, and Prediction. 2nd ed. Springer-Verlag, 2009. [URL](https://hastie.su.domains/ElemStatLearn/)

Jessica Zosa Forde, A. Feder Cooper, Kweku Kwegyir-Aggrey, Chris De Sa, and Michael Littman. "Model Selection's Disparate Impact in Real-World Deep Learning Applications." arXiv preprint, submitted September 7, 2021. [URL](https://arxiv.org/abs/2104.00606)

Inioluwa Deborah Raji, I. Elizabeth Kumar, Aaron Horowitz, and Andrew Selbst. “The Fallacy of AI Functionality.” FAccT '22: 2022 ACM Conference on Fairness, Accountability, and Transparency, June 2022, 959–72. [URL](https://doi.org/10.1145/3531146.3533158)

Amandalynne Paullada, Inioluwa Deborah Raji, Emily M. Bender, Emily Denton, and Alex Hanna. “Data and Its (Dis)Contents: A Survey of Dataset Development and Use in Machine Learning Research.” Patterns 2, no. 11 (2021): 100336. [URL](https://doi.org/10.1016/j.patter.2021.100336)

Christopher M. Bishop. Pattern Recognition and Machine Learning. New York: Springer, 2006. [URL](https://cis.temple.edu/~latecki/Courses/RobotFall08/BishopBook/Pages_from_PatternRecognitionAndMachineLearning1.pdf)

Md Johirul Islam, Giang Nguyen, Rangeet Pan, and Hridesh Rajan. "A Comprehensive Study on Deep Learning Bug Characteristics." arXiv preprint, submitted June 3, 2019. [URL](https://arxiv.org/abs/1906.01388)

Swaroop Mishra, Anjana Arunkumar, Bhavdeep Sachdeva, Chris Bryan, and Chitta Baral. "DQI: Measuring Data Quality in NLP." arXiv preprint, submitted May 2, 2020. [URL](https://arxiv.org/abs/2005.00816)

Doug Wielenga. "Paper 073-2007: Identifying and Overcoming Common Data Mining Mistakes." SAS Global Forum 2007: Data Mining and Predictive Modeling, SAS Institute, 2007. [URL](https://support.sas.com/resources/papers/proceedings/proceedings/forum2007/073-2007.pdf)

### Software Resources

- [Drifter](https://github.com/ModelOriented/drifter) library (performance assessment)
- [Manifold](https://github.com/uber/manifold) library (performance assessment)
- [MLextend](http://rasbt.github.io/mlxtend/) library (performance assessment)
- [PiML](https://github.com/SelfExplainML/PiML-Toolbox) library (explainable models, performance assessment)
- [SALib](https://github.com/SALib/SALib) library (performance assessment)
- [What-If Tool](https://pair-code.github.io/what-if-tool/index.html#about) (performance assessment)

# Citations

[1] [NIST AI RMF 1.0 PDF](/source/NIST.AI.100-1.pdf)
[2] [NIST AI RMF Playbook JSON](/artifacts/data/ai-rmf-playbook.json)
