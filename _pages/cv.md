---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A downloadable PDF version of my CV is available here: [Difei Gu's Curriculum Vitae](../files/Difei_Gu_CV.pdf).

Education
======
* Ph.D. in Computer Science, Rutgers University, Sept. 2023 – Expected 2028 (GPA: 3.9/4.0)
  * Advisor: Prof. Dimitris Metaxas
* B.S. in Electrical and Computer Engineering (Co-operative Program), University of Waterloo, Sept. 2016 – May 2021 (GPA: 3.9/4.0)

Work experience
======
* Jun 2026 – Present: Research Intern (Agentic AI), Siemens Healthineers – Digital Technology & Innovation (DTI), Princeton, NJ
  * Co-supervised by Han Liu and Sasa Grbic
  * Agentic autoresearch framework for self-improving adaptation of medical foundation models; best intern poster award
* Aug 2021 – May 2023: Research Intern, Centre for Perceptual and Interactive Intelligence (CPII), Hong Kong SAR
  * Co-supervised by Prof. Hongsheng Li and Prof. Xiaofan Zhang
* Sept 2019 – Dec 2019: Systems Software Developer (DevOps), BlackBerry, Ottawa, Canada
* Jan 2019 – Apr 2019: Software Development Intern (R&D), Northern Digital Inc., Waterloo, Canada

Skills
======
* Deep Learning & Frameworks: PyTorch, HuggingFace Transformers, CLIP, NumPy, scikit-learn
* Vision & Multimodal: VLM, LLM, Sparse Autoencoders, Reasoning Models, CNN/ViT
* Optimization & Training: Distributed Training (DDP/NCCL), Mixed Precision
* Specialized Areas: Agentic AI, Reasoning Systems, Model Interpretability, VLM, Medical Imaging, Image Segmentation

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
