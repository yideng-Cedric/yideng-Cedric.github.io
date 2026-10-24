---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download CV (PDF)]({{ base_path }}/files/Resume_YiDeng_PhD.pdf){: .btn .btn--primary}

# Education

**Incoming Ph.D. Student in Computer Science**, University of Texas at Arlington, Spring 2027

**M.E. in Computer Engineering**, University of Virginia, Aug. 2025 – Dec. 2026 (expected)
- GPA: 3.70 / 4.00
- Relevant coursework: Wireless Sensing, Machine Learning, Human-Computer Interaction (HCI)

**B.Eng. in Electronic & Computer Engineering**, Shenzhen MSU-BIT University, Aug. 2021 – Jun. 2025
- GPA: 3.71 / 4.00
- Core courses: Modern Communication Principles, Database Principles, Machine Learning

# Research Interests

- Wireless and multimodal sensing
- Artificial Intelligence of Things (AIoT) and edge intelligence
- Cyber-physical systems (CPS)

# Research Experience

**Multimodal Physiological Sensing in Driving Experiments**  
*Research Assistant, University of Louisville | Mar. 2026 – Aug. 2026*

- Built preprocessing and quality-control pipelines for 16-channel EEG, three-wavelength PPG, and EDA, including filtering, artifact screening, channel interpolation, signal-quality checks, and temporal alignment.
- Characterized motion artifacts, signal-quality limitations, and inter-participant variability; established trial- and event-level quality criteria.
- Extracted heart rate, frontal theta, occipital alpha, and skin conductance features across driving-event stages.

**Cloud–Edge EEG Emotion Recognition under Communication Constraints**  
*Nov. 2024 – Dec. 2025 | First-author publications: CloudCom 2025 and IEEE OJ-COMS*

- Developed an end-to-end EEG emotion recognition pipeline using CNN–LSTM–Attention models in PyTorch.
- Simulated packet loss, lossy compression, and bandwidth constraints to evaluate their effects on recognition accuracy.
- Developed GAN- and diffusion-based reconstruction modules for degraded EEG signals.
- Evaluated accuracy, latency, and transmission-cost trade-offs for cloud-edge biosignal inference.

**Performance Analysis of Mamba State-Space Models**  
*Apr. 2024 – Jul. 2024 | First-author publication: SmartIoT 2024*

- Investigated the effects of learning rate, batch size, and state expansion factor on Mamba training time and accuracy.
- Built reproducible benchmarks using SST-2, IMDB, and AG News.
- Analyzed training stability and performance trade-offs across configurations.

# Publications

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

# Academic Service

- **Reviewer**, *IEEE Transactions on Industrial Informatics*, Aug. 2026
- **Artifact Evaluator**, OSDI '26 Artifact Evaluation Committee (AEC), 2026

# Other Projects

**Contactless Respiration Sensing with WiFi CSI and FMCW Radar**  
*Wireless Sensing coursework, University of Virginia | Aug. 2025 – Dec. 2025*

- Tested open-source WiFi CSI and FMCW radar pipelines for respiration estimation, including signal preprocessing and frequency-domain analysis.

**Construction and Application of Raman Spectrometer**  
*Shenzhen MSU-BIT University | Apr. 2023 – May 2024*

- Built and calibrated Raman and UV-Vis absorption spectrometers, ensuring optical-path alignment and spectral accuracy.
- Developed additional measurement functions for the department's first in-house Raman spectrometer.

# Industry Experience

**Research and Development Engineer (Intern)**, Fusheng Innovation (Chengdu) Technology Co., Ltd.  
*Apr. 2024 – Sep. 2024*

- Implemented backend modules in Go and integrated broker APIs for trading requests and order management.
- Maintained relational databases and tested API behavior under network latency and failure scenarios.

**Product Intern**, Shenzhen UBTECH Robotics Corp., Ltd.  
*Nov. 2024 – Feb. 2025*

- Tested AI-based obstacle recognition in robotic vacuum products, including sensing and navigation edge cases.
- Analyzed test results and user feedback to support product improvements.

# Technical Skills

- **Programming:** Python, C/C++, Go
- **Machine Learning:** PyTorch, CNN, LSTM, attention, Mamba, GAN, diffusion models, time-series modeling
- **Signal Processing & Sensing:** EEG, PPG, EDA; physiological feature extraction; coursework exposure to WiFi CSI and FMCW radar
- **Embedded & Control:** MATLAB/Simulink, basic PID controller design and tuning
- **Networking & Tools:** TCP/IP, HTTP, TCP/UDP development in Python, Linux, SQLite, Git
- **Other:** Raman and UV-Vis spectroscopy

# Honors and Awards

- University-level Third-class Academic Scholarship, Shenzhen MSU-BIT University, 2022–2023 (Top 30%)
- Third Prize, 15th Blue Bridge Cup National Software and Information Technology Competition (C/C++), Guangdong Province, Apr. 2024
