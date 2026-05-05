---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

My full curriculum vitae is available here:

[Download CV]({{ base_path }}/files/Resume_YiDeng_PhD.pdf){: .btn .btn--primary}

Education
======

* **M.S. in Computer Engineering**, University of Virginia, Aug. 2025 – Dec. 2026 expected  
  * GPA: 3.50 / 4.00
  * Relevant coursework: Wireless Sensing, AI Hardware, Generative AI

* **B.Eng. in Electronic and Computer Engineering**, Shenzhen MSU-BIT University, Aug. 2021 – Jun. 2025  
  * GPA: 3.71 / 4.00, Top 30%
  * Core coursework: Modern Communication Principles, Database Principles, Machine Learning

Research Interests
======

* AI for healthcare, daily health monitoring, and personalized health intelligence
* Physiological signal processing and machine learning for EEG and wearable sensing
* Reliable and deployable healthcare AI systems on cloud-edge platforms
* Generative models for biosignal reconstruction, augmentation, and digital health applications

Selected Research Experience
======

**Cloud-Edge EEG Emotion Recognition under Communication Constraints**  
*Nov. 2024 – Dec. 2025*

* Designed and implemented an end-to-end EEG emotion recognition pipeline using CNN-LSTM-Attention models in PyTorch.
* Studied cloud-edge deployment under communication constraints, including packet loss, lossy compression, and bandwidth limitations.
* Developed GAN- and diffusion-based reconstruction methods to recover degraded EEG signals and improve downstream inference.
* Analyzed trade-offs among accuracy, latency, and transmission cost for deployable biosignal inference systems.

**Performance Analysis of Mamba State-Space Models**  
*Apr. 2024 – Jul. 2024*

* Designed controlled experiments to study how hyperparameters affect the training time and accuracy of Mamba-based models.
* Built an automated benchmarking pipeline across multiple NLP datasets, including SST-2, IMDB, and AG News.
* Analyzed performance trade-offs and training stability under different hyperparameter settings.

**Construction and Application of Raman Spectrometer**  
*Apr. 2023 – May 2024*

* Built and calibrated Raman and UV-Vis absorption spectrometers from optical components.
* Implemented additional measurement functions and supported the development of an in-house spectrometer for educational and research use.

Publications
======

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

Industry Experience
======

**Research and Development Engineer Intern**, Fusheng Innovation (Chengdu) Technology Co., Ltd.  
*Apr. 2024 – Sep. 2024*

* Designed and implemented backend modules in Go for a trading system.
* Integrated broker APIs for order handling and status updates.
* Maintained relational databases and supported API testing under network latency and failure scenarios.

**Product Intern**, Shenzhen UBTECH Robotics Corp., Ltd.  
*Nov. 2024 – Feb. 2025*

* Supported functional testing of AI-based obstacle recognition in robotic vacuum products.
* Collected and analyzed user feedback and test results to support product iteration.

Technical Skills
======

* **Programming:** Python, C/C++, Go, MATLAB, Verilog
* **Machine Learning:** PyTorch, CNN, LSTM, attention models, Mamba, GANs, diffusion models
* **Signal Processing:** EEG preprocessing and analysis, biosignal modeling, time-series feature extraction
* **Systems:** cloud-edge computing, wearable sensing, embedded AI, Linux, Git
* **Other:** Raman spectroscopy, UV-Vis spectroscopy, SQLite, TCP/IP, HTTP

Honors and Awards
======

* University-level Third-class Academic Scholarship, Shenzhen MSU-BIT University, 2022–2023
* Third Prize, 15th Blue Bridge Cup National Software and Information Technology Competition, Guangdong Province, Apr. 2024
