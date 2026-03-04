---
layout: default
title: DNSC 6330 – Responsible ML
---

<link rel="stylesheet" href="{{ site.baseurl }}/assets/css/custom.css">

<div class="site-header-row">
  <div class="site-header-text">
    <h1>DNSC 6330 – Responsible ML</h1>
    <p>Responsible Machine Learning as Sociotechnical System</p>
  </div>
  <div class="site-header-logo">
    <img src="{{ site.baseurl }}/assets/img/GWBusiness.jpeg" alt="DNSC Logo">
  </div>
</div>

## Course Description

Artificial intelligence systems increasingly shape credit decisions, hiring pipelines, health risk scoring, insurance underwriting, and public policy implementation. As these systems scale, so do their legal, operational, and reputational risks. This course prepares future business leaders, model developers, risk managers, and governance professionals to design, evaluate, and oversee machine learning systems with rigor, accountability, and defensibility.

Responsible Machine Learning examines machine learning as a sociotechnical system embedded within institutional, regulatory, and market environments. Students move beyond high-level ethical principles to operational practice: measuring bias, diagnosing model behavior, stress-testing robustness, identifying security vulnerabilities, and designing post-deployment monitoring frameworks.

This course treats Responsible Machine Learning as a discipline of stewardship. Numeric grades are assigned for administrative purposes, but mastery is defined by audit-level rigor, sound reasoning, and the ability to justify decisions under legal, ethical, and operational scrutiny. Students are prepared not only to build models, but to defend them. The result is a practitioner-ready foundation for roles in AI governance, model risk management, ML audit and assurance, and responsible AI leadership within business and regulatory environments.

This repository serves as the working lab environment for the course.

## Course Philosophy

Responsible ML is built on three pillars:

1. **Measurement before opinion**
2. **Diagnostics before remediation**
3. **Documentation before deployment**

Each lecture is structured as a lab module with:

- Conceptual framing
- Mathematical formalization
- Code experiments
- Risk diagnostics
- Governance artifacts

## Class Modules

1. [Lecture 01 — Foundations of the Alignment Problem:](Lecture-01-alignment/) Introduces the alignment problem through real world AI and ML failures, establishes why ML systems are sociotechnical in nature, clarifies the role of Responsible ML and management, and situates the field within emerging Responsible AI career pathways. Responsible Machine Learning will be framed as a risk-benefit framework throughout the course.
2. [Lecture 02 – Explainability and Interpretability as Diagnostic Tools:](Lecture-02-xAI/) Examines explainability and interpretability as diagnostic practices rather than a checkbox, comparing model level and system level explanations, assessing tools such as LIME, SHAP, and counterfactuals, and analyzing cases where explainability failed in production across stakeholder contexts.
3. [Lecture 03 – Algorithmic Bias Measurement:](Lecture-03-bias/) Focuses on identifying and measuring algorithmic bias, including allocational, representational, and quality of service harms, with grounding in U.S. anti-discrimination laws, fairness definitions, proxy discrimination, intersectionality, and hands-on subgroup evaluation using real datasets.
4. [Lecture 04 – Robustness, Generalization, and Dataset Drift:](Lecture-04-generalization/) Explores model robustness and failure modes over time, including spurious correlations, stress testing, concept drift versus data drift, and long horizon failures, with applied testing in domains such as credit scoring.
5. [Lecture 05 – ML Security and Abuse Pathways:](Lecture-05-security/) Analyzes security threats and misuse of ML systems, including adversarial examples, data poisoning, model extraction, and abuse of generative models, supported by practical exercises in ML security testing.
6. [Lecture 06 – Responsible Deployment and Monitoring:](Lecture-06-monitoring/) Covers post-deployment responsibilities such as data cards, model cards and system cards, continuous evaluation, alerting and rollback mechanisms, human-in-the-loop design, and organizational roles required for responsible deployment and monitoring.
7. [Lecture 07 – Responsible AI Management and Global Regulatory Frameworks:](Lecture-07-govAI/) Addresses system-level AI risks associated with foundation and language models, reviews global governance frameworks such as NIST AI RMF, EU AI Act, and ISO/IEC standards, and applies policy analysis through hands-on stakeholder and regulatory gap discussions.

## Minimum Standard for Capstone Projects
📁 Folder: [Capstone](./Lecture-08-capstone/)

Every capstone project must answer:

1. What is the optimization objective?
2. What are the known failure modes?
3. How are subgroup errors measured?
4. What risks remain after mitigation?
5. Is deployment defensible?

## Evaluation Standard

Students are evaluated on:

- Analytical rigor
- Working code implemented in Python (preferred) or R
- Reproducibility
- Documentation clarity
- Justification under scrutiny

## License

This project is dual-licensed under:

- Apache License 2.0 (see LICENSE-APACHE)
- Creative Commons Attribution 4.0 (see LICENSE-CC-BY)

You may choose either license.