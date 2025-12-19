---
title: "Curriculum Vitae"
layout: "single"
toc: true
hideMeta: true
---

<!-- =========================================================
     FULL‑PAGE BACKGROUND WRAPPER
     The entire CV content sits inside this container so that
     the themed background covers the whole page.
    <a href="URL" class="cv-link">DISPLAY TEXT</a>
     ========================================================= -->
<div class="make_bg bg_cv">

## Nima Taghipour Bazargani

  <!-- Top Futuristic Tagline -->
  <div style="max-width:1100px; margin:0 auto 2rem auto; text-align:center;">
    <p style="margin:0; font-size:1.12rem; letter-spacing:0.09em; text-transform:uppercase;">
      <span style="font-size:1.45rem;">⚡</span> Power Systems &nbsp;·&nbsp;
      <span style="font-size:1.45rem;">🤖</span> Machine Learning &amp; Intelligence &nbsp;·&nbsp;
      <span style="font-size:1.45rem;">🕸</span> Networked Dynamical Systems
    </p>
  </div>

[//]: # (Pasadena, California  )

[//]: # (Email: ntaghip1@asu.edu  )

[//]: # (LinkedIn: https://www.linkedin.com/in/nima-t-bazargani)

<br/>

<a class="hero-btn primary" href="/cv/CV_Nima_T_Bazargani_public.pdf" target="_blank">
⬇️ Download Full CV (PDF)
</a>

---

## 🧭 Contents

- [Professional Profile](#professional-profile)
- [Experience](#experience)
- [Education & Coursework](#education--coursework)
- [Projects & Publications](#projects--publications)
- [Recognition & Acknowledgments](#recognition--acknowledgments)

---

## Professional Profile

I am an electrical engineer specializing in **power systems**, **machine learning**, and **networked‑system analytics**.  
My work combines physics‑based modeling with modern data‑driven methods to improve grid monitoring, stability assessment, electricity‑market behavior, and infrastructure resilience.  
My experience spans both **academic research** and **industry‑facing engineering**, focusing on scalable, real‑time, and operationally relevant solutions for large‑scale electric power systems.

### Key technical themes

- **PMU analytics:** event identification, oscillation detection, wide‑area monitoring, and synchrophasor‑driven insights.  
- **Machine learning:** time‑series forecasting, classification, feature extraction, semi‑supervised and continual learning (including MAML) for rare events.  
- **Electricity markets:** simulation and analytics for SCUC/SCED, congestion studies, price formation, risk analysis, and planning.  
- **Resilience & microgrids:** battery storage sizing, resiliency metrics, microgrid protection, and restoration planning.  
- **Networked infrastructures:** multi‑layer graph formulations for power and communication systems; virtual network embedding under uncertainty.

### Core expertise

- **Power Systems:** wide‑area monitoring using PMUs; power system dynamics, stability, and inertia forecasting; transmission and distribution modeling; planning and operational studies.  
- **Machine Learning & Data Science:** time‑series forecasting and classification; semi‑supervised learning for rare events; spatio‑temporal feature extraction; reproducible ML pipelines integrating Python and C++ ecosystems.  
- **Markets & Optimization:** Security‑Constrained Unit Commitment (SCUC) and Economic Dispatch (SCED); scenario‑based congestion and risk analysis; optimization‑informed decision support; integration of external drivers (weather, fuel, outages) into large simulation workflows.

### Technical skills

- **Programming & ML:** Python (NumPy, pandas, scikit‑learn, PyTorch, TensorFlow/Keras), MATLAB, GAMS, SQL, C++.  
- **Analytics & methods:** time‑series modeling, optimization, semi‑supervised and incremental learning, modal analysis, dimensionality reduction, data engineering, reproducible pipelines.  
- **Cloud & infra:** Git/GitHub, Linux, REST APIs, Google Cloud Platform, AWS.  
- **Power system tools:** PSS®E, PowerWorld, DIgSILENT PowerFactory, PSLF, DSATools, TARA, DAYZER.

---
## Experience
- **Power System Engineer | <a href="https://www.electricpowergroup.com/" class="cv-link">Electric Power Group (EPG)</a>**  
  *Pasadena, California | Sep 2024 – Jul 2025*  
  Developed a real-time **inertia and system-strength forecasting** capability using high-speed synchrophasor (PMU) streams and integrated it into a production C++ analytics platform. Designed a Python-based machine-learning framework interoperable with the existing C++ product stack and applied **Model-Agnostic Meta-Learning (MAML)** to adapt models to short-term grid shifts while reducing catastrophic forgetting. Crafted physics-informed features for operator-facing situational-awareness tools and championed incremental learning on live PMU streams.

- **Network Model Analyst | <a href="https://www.cwpenergy.com/" class="cv-link">CWP Energy</a>**  
  *Montreal, Canada (Remote) | Sep 2023 – Jun 2024*  
  Conducted large-scale **SCUC/SCED simulations** for major U.S. markets (MISO, SPP, PJM, ERCOT) to support day-ahead strategy, planning, and risk analysis. Enhanced simulation pipelines by integrating external drivers(e.g., weather, fuel prices, outage schedules) and utilizing cloud compute to scale long-horizon studies for congestion risk and Financial Transmission Right (FTR) analysis. Built scalable Python + Google Cloud workflows for market scenario analysis and produced congestion and price-risk analytics that informed trading and planning decisions.

- **Data Scientist Intern | <a href="https://www.drivepowerline.com/" class="cv-link">Drive Powerline</a>** *(formerly gigElev)*  
  *San Francisco, California (Remote) | May 2022 – Aug 2022*  
  Designed and deployed REST API pipelines to ingest, clean, and organize electricity market and grid datasets (including CAISO) for downstream analytics. Developed and deployed near-real-time machine-learning models to forecast operational grid metrics, providing improved situational awareness and decision support for internal analytics tools.

- **Graduate Research Associate | <a href="https://www.asu.edu/" class="cv-link">Arizona State University</a>**  
  *Tempe, Arizona | Aug 2019 – Sep 2023*  
  Developed methods for **real-time event identification** using high-dimensional spatio-temporal PMU measurements. Built a complete event-identification pipeline (event generation via PSS®E Python API, modal-analysis feature extraction, semi-supervised benchmarking, and ML classification) and contributed to PSERC- and NSF-funded projects on oscillation detection, modal feature extraction, and anomaly classification. Applied **modal analysis** and semi-supervised learning methods to rare events and collaborated on a U.S.–Israel Energy Center initiative that produced an open-source PMU analytics framework — see the arXiv paper for details ([arXiv](https://arxiv.org/abs/2309.10095)). Research funding included NSF (OAC-1934766), PSERC (S-87) ([final report](https://documents.pserc.wisc.edu/documents/publications/reports/2021_reports/S_87_Final_Report.pdf)), and a BIRD-sponsored cybersecurity-in-energy program ([Energy Center](https://us-isr-energycenter.org/energy_cyber/USIE.html)).

- **Guest Researcher | <a href="https://www.tu-darmstadt.de/" class="cv-link">Technical University of Darmstadt</a>** *(CRC 1053 MAKI)*  
  *Darmstadt, Germany | Oct 2018 – May 2019*  
  Worked on **reliable virtual network embedding** for cyber-physical energy systems as part of the Collaborative Research Center 1053 MAKI – Multi-Mechanisms Adaptation for the Future Internet ([project page](https://www.maki.tu-darmstadt.de/forschung_maki/index.en.jsp)). Formulated the problem as a stochastic mixed-integer optimization for communication networks supporting energy automation and contributed to multi-layer network adaptation mechanisms under uncertainty. Collaborated closely with **Prof. Dr. Florian Steinke** ([homepage](https://www.eins.tu-darmstadt.de/eins/team/florian-steinke/)).

- **Project Advisor | <a href="https://www.linkedin.com/company/nirooresearchinstitute/" class="cv-link">Niroo Research Institute (NRI)</a>**  
  *Tehran, Iran | Aug 2017 – Jun 2018*  
  Led resilience-oriented modeling for national power-system infrastructure. Supported the definition, evaluation, and analysis of resilience metrics used in power system planning and developed graph-based restoration and vulnerability assessment modules for infrastructure resilience.
---


## Education & Coursework
**Degrees & theses**

| Degree | University / Period | Thesis / Focus | Advisors |
|---|---|---|---|
| **Ph.D., Electrical Engineering** | Arizona State University (2019–2023) | Real-Time Identification of Power System Events Using Phasor Measurement Unit Data | <a href="https://sites.google.com/site/okosut/" class="cv-link">Oliver Kosut</a>; <a href="https://faculty.engineering.asu.edu/sankar/" class="cv-link">Lalitha Sankar</a> |
| **M.Sc., Electrical Engineering (Power Systems)** | K. N. Toosi University of Technology (2015–2018) | Optimal Sizing & Allocation of Battery Energy Storage Systems for Microgrid Resilience | <a href="https://wp.kntu.ac.ir/bathaee/index.htm" class="cv-link">S. M. T. Bathaee</a> |
| **B.Sc., Electrical Engineering** | Shahid Beheshti University (2008–2014) | Design & Construction of a Static Frequency Converter for Transformer Testing | <a href="https://encpe.sbu.ac.ir/en/~m_aghashabani" class="cv-link">Mohammad Hossein Aghashabani</a> |

**Selected Ph.D. coursework (ASU)**  
Machine Learning for Smart Grid (<a href="https://yweng3.github.io/" class="cv-link">Yang Weng</a>);  
Wide-Area Measurement System Applications (<a href="https://faculty.engineering.asu.edu/pal/" class="cv-link">Anamitra Pal</a>);  
Random Signal Theory (<a href="https://gautamdasarathy.com/" class="cv-link">Gautam Dasarathy</a>);  
Linear Algebra & Convex Optimization (<a href="https://faculty.engineering.asu.edu/nedich/" class="cv-link">Angelia Nedić</a>);  
Foundations of Machine Learning (<a href="https://faculty.engineering.asu.edu/sankar/" class="cv-link">Lalitha Sankar</a>);  
Topics in Reinforcement Learning (<a href="https://search.asu.edu/profile/3410924" class="cv-link">Dimitri P. Bertsekas</a>);  
Power System Stability & Dynamics (<a href="https://faculty.engineering.asu.edu/vvittal/" class="cv-link">Vijay Vittal</a>).

**Selected M.Sc. coursework (K. N. Toosi University of Technology)**  
Power System Dynamics; Power System Reliability; Power System Planning; Advanced Power System Protection; Power System Transients; Flexible AC Transmission Systems (FACTS); Smart Grids.

**Selected B.Sc. coursework (Shahid Beheshti University)**  
Power System Analysis; Power System Operation & Dispatch; Distribution System Planning & Expansion; Power Distribution & Consumption Management; Electrical Machines; Power Electronics.

---

## Projects & Publications

### Publications & presentations

• **Nima T. Bazargani, Lalitha Sankar, Oliver Kosut** — *A Semi‑Supervised Approach for Power System Event Identification*, arXiv (2024).  
• **Rajasekhar Anguluri, Nima T. Bazargani, Oliver Kosut, Lalitha Sankar** — *Source Localization in Linear Dynamical Systems Using Subspace Model Identification*, IEEE Conference on Control Technology and Applications (CCTA 2023).  
• **Nima T. Bazargani, Gautam Dasarathy, Oliver Kosut, Lalitha Sankar** — *A Machine Learning Framework for Event Identification via Modal Analysis of PMU Data*, IEEE Transactions on Power Systems (2022).  
• **Rajasekhar Anguluri, Nima T. Bazargani, Oliver Kosut, Lalitha Sankar** — *A Complex‑LASSO Approach for Localizing Forced Oscillations in Power Systems*, IEEE Power & Energy Society (PES) General Meeting (2022).  
• Additional publications and conference presentations are listed in the PDF CV.

### Graduate term projects (M.Sc.)

- **SCUC under AC power flow:** Implemented security‑constrained unit commitment with start‑up scheduling under AC power flow constraints.  
- **Microgrid protection:** Analyzed protection strategies for low‑voltage microgrids using microprocessor‑based protective relays.  
- **Resilient microgrid sizing:** Developed simulation and optimal sizing of renewable resources on a NASA Ames microgrid testbed.  
- **Smart home simulation:** Designed a smart home on an IEEE 4‑bus test system with market‑clearing prices and customer incentives.  
- **Optimal switch placement:** Performed optimal switch placement for reliability improvement and customer interruption cost minimization (Roy Billinton Test System).


### Other projects & studies

- **PMU analytics & machine learning:** Developed semi-supervised event identification and modal-analysis-based classifiers; built and released an <a href="https://github.com/SankarLab/PSMLEI-public" class="cv-link">open-source PMU event identification package (PSMLEI)</a> implementing a semi-supervised framework for classifying disturbance events from high-dimensional PMU data under sparse labels (self-training, pseudo-label refinement, and consistency constraints), combining spectral/modal signatures with learned temporal embeddings, and demonstrating robust generalization across low-label regimes and varying operating conditions.  
- **System dynamics & oscillations:** Worked on complex-LASSO forced oscillation localization and subspace-based source localization; examined dynamical-system identification using spatio-temporal data.  
- **Market analysis & resilience:** Conducted multi-ISO SCUC/SCED studies, congestion modeling, and probabilistic hurricane resilience assessment; built scenario pipelines for congestion and risk analysis; explored financial transmission right (FTR) strategies.

*A more complete list of technical work is available on the* **[Projects page](/projects/)**.

---

## Recognition & Acknowledgments

### Honors & professional service

- Ranked 2nd in M.Sc. cohort at K. N. Toosi University of Technology.  
- Ranked 240 out of 30 000+ in the Iran National Graduate Entrance Examination.  
- IEEE Region 8 Paper Contest finalist (Middle East & Europe).  
- Vice‑President, Iranian Student Association (ISA) at Arizona State University.  
- Social Chair, IEEE Power & Energy Society (PES) student chapter committee at Arizona State University.  
- Reviewer for IEEE Transactions on Power Systems, IEEE Power & Energy Society General Meeting, International Journal of Electrical Power & Energy Systems, and the International Power System Conference (PSC).
### Academic mentorship & influential faculty

The following faculty members played a significant role in shaping my technical foundation, research interests, and professional direction (listed alphabetically):

- **<a href="https://encpe.sbu.ac.ir/en/~m_aghashabani" class="cv-link">Mohammad Hossein Aghashabani</a>** — Shahid Beheshti University  

- **<a href="https://scholar.google.com/citations?user=Wg6ldcIAAAAJ&hl=en" class="cv-link">Mohammad Reza Aghamohammadi</a>** — K. N. Toosi University of Technology  

- **<a href="https://wp.kntu.ac.ir/amraee/index.htm" class="cv-link">Touraj Amraee</a>** — K. N. Toosi University of Technology  

- **<a href="https://wp.kntu.ac.ir/bathaee/index.htm" class="cv-link">Seyed Mohammad Taghi Bathaee</a>** — K. N. Toosi University of Technology  

- **<a href="https://ir.linkedin.com/in/alireza-fereidunian-6151748" class="cv-link">Alireza Fereidounian</a>** — K. N. Toosi University of Technology  

- **<a href="https://encpe.sbu.ac.ir/~m_ghazizadeh/home" class="cv-link">Mohammad Sadegh Ghazi-Zadeh</a>** — K. N. Toosi University of Technology  

- **<a href="https://encpe.sbu.ac.ir/~gh_latif" class="cv-link">Gholam Reza Latif Shabgahi</a>** — K. N. Toosi University of Technology  

- **<a href="https://encpe.sbu.ac.ir/en/~m_pourgholi" class="cv-link">Mahdi Pourgholi</a>** — Shahid Beheshti University  

- **<a href="https://encpe.sbu.ac.ir/en/~m_rafiee" class="cv-link">Mansoor Rafiee</a>** — Shahid Beheshti University  

- **<a href="https://encpe.sbu.ac.ir/en/~m_setayesh" class="cv-link">Mehrdad Setayesh Nazar</a>** — Shahid Beheshti University  

- **<a href="https://www.salford.ac.uk/our-staff/vahid-vahidinasab" class="cv-link">Vahid Vahidinasab</a>** — University of Salford (Chair in Sustainability, Salford Business School; formerly Shahid Beheshti University)


### Abbreviations

- **PMU** — Phasor Measurement Unit  
- **WAMS** — Wide‑Area Monitoring System  
- **SCUC** — Security‑Constrained Unit Commitment  
- **SCED** — Security‑Constrained Economic Dispatch  
- **MAML** — Model‑Agnostic Meta‑Learning  
- **ISO** — Independent System Operator  
- **FTR** — Financial Transmission Right  
- **FACTS** — Flexible AC Transmission Systems  

<br/>

<!-- Navigation Buttons -->
<div style="margin-top:1.4rem; text-align:center;">
  <a href="/about/" class="hero-btn primary" style="margin-right:0.5rem;">about</a>
  <a href="/research/" class="hero-btn secondary" style="margin-right:0.5rem;">research</a>
  <a href="/projects/" class="hero-btn secondary" style="margin-right:0.5rem;">projects</a>
  <a href="/posts/" class="hero-btn secondary" style="margin-right:0.5rem;">blog</a>
  <a href="/cv/" class="hero-btn primary" style="margin-right:0.5rem;">cv</a>
  <a href="/contact/" class="hero-btn ghost">contact</a>
</div>

</div>
