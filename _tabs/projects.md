---
layout: page
title: Projects
icon: fas fa-flask
order: 3
---

An overview of current and recent research initiatives conducted within the **Applied AI Research Group** at Horizon Campus and collaborative international networks.

---

## 1. Multi-Modal Industrial Hazard & Fire Detection (2025 – Present)

![Industrial Safety](https://img.shields.io/badge/Domain-Computer%20Vision%20%26%20IoT-blue) ![Status](https://img.shields.io/badge/Status-HIRS%202025%20%7C%20Full%20Paper%20In%20Prep-brightgreen)

- **Lead Supervisor**: Isuru Madusanka Samarappulige
- **Student Researchers**: P. H. K. Arachchi, W. P. G. S. Madushani, R. A. K. W. Madhushanki, J. M. L. L. Karunarathna
- **Key Architectures**: YOLOv8, CLIP, LLaVA, IoT sensor telemetry, Edge deployment

Traditional smoke and heat detectors in industrial settings suffer from high false-alarm rates and slow response times, while basic optical camera systems struggle with visual occlusions and lighting extremes. 

This project explores a **multi-modal fusion architecture** that combines:
1. Real-time edge object detection using **YOLOv8** for rapid flame and smoke contour bounding.
2. High-level semantic scene understanding using **Vision–Language Models (VLMs)** such as CLIP and fine-tuned LLaVA to distinguish real hazards from benign heat/steam sources.
3. Corroborative multi-sensor IoT telemetry (air quality, thermal gradient, carbon monoxide levels) streamed into an edge decision layer.

*Outcome*: Extended abstract accepted at HIRS 2025; comprehensive journal manuscript currently in preparation.

---

## 2. AI Coding Assistants in Higher Education Computing (2025 – Present)

![Pedagogy](https://img.shields.io/badge/Domain-AI%20in%20Education-orange) ![Status](https://img.shields.io/badge/Status-Preprint%20at%20TechRxiv-blue)

- **Lead Investigator**: Isuru Madusanka Samarappulige
- **Co-Investigators**: K. Ekanayake, N. T. Jayathilake
- **Target Technologies**: GitHub Copilot, OpenAI ChatGPT, Automated Code Evaluation

The rapid adoption of generative AI programming tools presents both unprecedented educational opportunities and serious pedagogical challenges for introductory computing students.

This study implements a **rigorous mixed-methods empirical investigation ($n = 60$)** assessing how novice programmers in Sri Lanka interact with LLM code assistants:
- Quantitative metrics evaluating code correctness, syntactical accuracy, cyclomatic complexity, and test-case coverage.
- Qualitative analysis of cognitive offloading, debugging autonomy, conceptual comprehension, and academic integrity.
- Pedagogical guidelines and assessment frameworks designed to integrate AI coding tools responsibly into undergraduate curricula.

*Outcome*: Preprint submitted to TechRxiv; curriculum recommendations adopted in undergraduate lab modules.

---

## 3. Low-Resource Language Technologies: Sinhala NLP Corpus (2025 – 2026)

![NLP](https://img.shields.io/badge/Domain-Natural%20Language%20Processing-purple) ![Status](https://img.shields.io/badge/Status-Open%20Access%20Zenodo-green)

- **Investigators**: Isuru Samarappulige, K. Ekanayake
- **Outputs**: [Zenodo Dataset DOI: 10.5281/zenodo.21194859](https://doi.org/10.5281/zenodo.21194859) • [Zenodo Tool DOI: 10.5281/zenodo.21195380](https://doi.org/10.5281/zenodo.21195380)

Low-resource languages such as Sinhala face persistent challenges in NLP research due to a lack of high-quality, large-scale open-source training data. 

To bridge this divide:
- Developed the **Sinhala Stories Dataset Creator (v1.0)**, an automated data extraction and cleaning engine tailored to Sinhala script normalization, deduplication, and ethical filtering.
- Curated and published a **10-million-row Sinhala narrative corpus**, providing researchers worldwide with structured text for language model pre-training, fine-tuning, and linguistic evaluation.

---

## 4. Agentic AI & Autonomous DevSecOps Infrastructure

![DevOps](https://img.shields.io/badge/Domain-DevSecOps%20%26%20Agentic%20AI-red) ![Status](https://img.shields.io/badge/Status-Research%20Prototype-yellow)

- **Collaborators**: B. L. A. I. Maduwanthi, V. A. D. L. Karunarathna, T. V. M. Weerasooriya, I. A. Dayananda, I. Samarappulige
- **Technologies**: Docker, Kubernetes, AWS, LLM Tool Calling, GitHub Actions

Investigating autonomous software delivery agents capable of analyzing continuous integration build logs, diagnosing deployment failures, verifying security vulnerability patches, and orchestrating cloud infrastructure with minimal human intervention.

