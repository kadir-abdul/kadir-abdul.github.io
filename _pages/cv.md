---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Practical skills
- **Coding:** Python, Java, SQL, Go, C, JavaScript, MATLAB, R
- **AI frameworks:** Hugging Face Transformers, TensorFlow, PyTorch, CNTK, OpenCV, scikit-learn
- **Data tools:** SQL, Pillow, NumPy, Matplotlib, Dash, Jupyter Notebook
- **Microservices & version control:** AWS, GCP, SLURM, IBM Cloud, Docker, Kubernetes, Git, CI/CD, MLflow, Kubeflow
- **Office & documentation:** Excel, Word, PowerPoint, LaTeX

## Experiences

### Researcher — German Research Center for Artificial Intelligence (DFKI), Saarbrücken (2020–Present)
- Lead explainable AI initiatives across language and vision models with a focus on healthcare deployment.
- Build and maintain ML DevOps pipelines that keep experimental and production systems synchronized.
- Deliver state-of-the-art tools including skin cancer detection, automatic shift planning, eye disease detection, and ML model explainers.

### Research Assistant — German Research Center for Artificial Intelligence (2018–2020)
- Advanced NLP projects such as co-reference resolution and custom PyTorch architectures.
- Designed visualization workflows to help stakeholders interpret complex model behavior.

### Research Assistant — IFOMIS, Saarland University (2016–2018)
- Shipped RESTful services for medical data integration.
- Built a Java-based Git client adopted by internal teams.

### Data Scientist — Radiant Export Import Enterprise, Dhaka (2015–2016)
- Drove sales analytics initiatives to surface actionable retail insights.

### Miscellaneous roles — Saarland University & BRAC University (2016–2018)
- Served as a programming tutor, mentoring students across software engineering and AI fundamentals.

## Project acquisition

### Active Learning in the Cloud — Google Cloud & DFKI Interactive Machine Learning Group (2023–2024)
- Developed an active learning backend on Google Cloud Platform for OCT segmentation workflows. Project link: [End-to-end active learning framework news](https://iml.dfki.de/news/end-to-end-active-learning-framework-for-medical-image-annotation/).

### Explainable AI for Tax Fraud Detection — Talentik GmbH (Software Campus) & DFKI (2024–2026)
- Building anomaly-detection tooling for financial accounting data with a strong explainability layer. Funding link: [DFKI project page](https://www.dfki.de/web/forschung/projekte-publikationen/projekt/iuml).

## Education

- **Ph.D. Candidate in Computer Science**, Oldenburg University, Oldenburg, Germany (2020–Present)  
  Focus: Explainable Deep Learning
- **M.Sc. in Computer Science**, Saarland University, Saarbrücken, Germany (2016–2020)  
  Focus: Machine Learning and Artificial Intelligence
- **B.Sc. in Electrical and Electronic Engineering**, BRAC University, Dhaka, Bangladesh (2011–2015)  
  Focus: Robotics and Automation

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Mentor for programming courses at Saarland University and BRAC University, guiding students through machine learning and software projects.
* Liaison between DFKI’s Interactive Machine Learning group and industry partners to translate research into deployable tools.
* Active contributor to cross-lab initiatives on trustworthy and explainable AI practices.
