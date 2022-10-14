---
layout: archive
title: "Resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Electrical and Computer Engineering, University of California, Davis, 2021 (expected)
  * *Thesis: Geometrical Frameworks for Wireless Access in Large Scale Multi-Antenna Networks*
  * Advisor: Prof. Zhi Ding 
* M.Sc. in Electrical Engineering with research thesis, Pontificia Universidad Católica de Chile, 2013
  * *Thesis: Acquisition algorithms for wireless sensor networks with multiple antenna technology*
* B.S. in Electrical Engineering, Pontificia Universidad Católica de Chile, 2013
  * *Graduation with Honors*

Research Projects and Experience
======
* Over-the-Air Collaborative Learning (2022-Present)
  * Developed an over-the-air computation collaborative learning framework in IoT based on detection theory, where sensors send their distributed measurements for hypothesis testing at the server, that enjoys good detection performance, low complexity and high resource efficiency. We are now studying theoretical results for collaborative detection using local sensor summaries under Bayesian and Neyman-Pearson frameworks, and a collaborative estimation framework under similar system models.
* Unsupervised User Scheduling via Manifold Clustering (2020-Present)
  * Proposed a new user scheduling strategy to mitigate co-channel interference, based on clustering similar user channels via Riemannian unsupervised learning and assign them into distinct resource sharing groups. We have improved these results with a per-cluster optimal assignment formualtion, and currently extending this model to multiband systems and multiantenna users.
* Grant-Free Access via Blind Signal Recovery (2018-2021)
  * Determined convergence guarantees for CMA-based signal recovery via non-regularized gradient-descent under finite number of samples. Proposed a low-complexity approach for blind multiple signal recovery with orthogonality constraints via Riemannian manifold optimization for grant-free access, with convergence guarantees for finite number of samples. 
Signal Processing at RF (2016-2019)
  * Designed an RF-level Direct-Sequence Spread Spectrum system for improved narrowband interference rejection in the analog domain. Co-designed spreading codes, timing recovery scheme, system parameters and a measurement testbed. 
* Hardware-Level System Identification via Neural Networks (2018)
  * Designed a SDR testbed for transceiver identification, which characterizes RF hardware characteristics of each transmitter-receiver pair by analyzing received signals. Collected and labeled signals to use as training data. The implemented LSTM network achieved >95% accuracy of correct identification. 
* Trans-layer Robust Header Compression (2017-2019)
  * Proposed a ROHC compression scheme via a POMDP model with trans-layer information, that considers the splitting/merging of PDCP packets at the MAC layer and MAC channel conditions. Achieved 8% performance improvement over timer-based ROHC control.
* Acquisition PHY Algorithms for MIMO Wireless Sensor Networks (2012-2013)
  * Designed ad-hoc Frame Detection, Carrier Recovery, Timing Recovery, and Channel Estimation algorithms for beamforming MIMO WSN, which exploited spatial diversity to improve energy consumption in low SNR conditions. Developed a fixed-point Simulink testbed, design architectures, and guidelines for FPGA implementation. Project partially funded by FONDEF under Grant D09I1094, Synopsis, and Coasin.


Skills
======
* Communication systems analysis and design
  * Performance analysis using MATLAB
  * Algorithm design, with emphasis on PHY and MAC layer
  * Characterization of communication systems
  * RTL guidelines for FPGA implementation
* Non-convex optimization
* Statistical Analysis
* Extensive use of MATLAB and Python

Professional Activities
=====
Memberships
* IEEE Member (2022), IEEE Student Member (2010)
* Industry Officer of the ECE Graduate Student Association, UC Davis (2019-2020)
* Vice-chair of IEEE Student Branch at Pontifical Catholic University of Chile (2010-2011)

Reviewer
* IEEE Transactions in Signal Processing, IEEE Transactions on Communications, IEEE Transactions on Cognitive Communications and Networking


Engineering Experience
======
* **R&D Project Lead** | GMS Technologies Ltda., Chile (2016-2020)
  * Designed an embedded datalogger system with radio communication and mining sensor interfaces, e.g. vibrating wire piezometer and time-domain reflectometer (TDR). Designed all schematics and PCBs, assembled 
all electronics and tested functionality and debugged using lab instrumentation. Supervised the development
of FPGA description language to control TDR hardware, using Xilinx Vivado IPs and a custom IP in Verilog.
  * Directed a team of 5 interns to improve the electronic projects mentioned above (embedded datalogger, vibrating wire piezometer interface, time-domain reflectometer). Directed the design of a mid-range mechanical
ventilator for COVID-19 paliative care, along a team of kinesiologists and interns.
* **Project Engineer** | Universidad del Desarrollo, Chile (2014-2016)
  * Technical Coordinator of the institutional alliance between Universidad del Desarrollo and Telefonica Chile
(a major telecommunications company), which aimed to foster the creation and adoption of data-driven
applications and supporting IoT technologies using both industry and academia efforts.
  * Developed and delivered the first version of "Semana-i", a campus-wide interdisciplinary experience where 2nd and 3rd year students from all majors participate full-time in projects proposed and developed by faculty and lecturers from all schools, possibly outside of their usual research fields, for 3 days. Regular classes are put on hold and these interdisciplinary projects count for semester grade. This project was inspired by a similar interdisciplinary program implemented by Instituto Tecnol\'ogico y de Estudios Superiores De Monterrey, México.
  * Developed projects related to technological innovation and lectured related courses and sessions.
* **R&D Engineer** | Pontifical Catholic University of Chile, Chile (2013-2014)
  * Designed a wireless sensor network testbed (schematics, PCBs, assembly, enclosure, mounts). Design was
modular and considered micro-controller, battery management with solar panel, sensor interfaces, and RF
communications.
  * Submitted two patent applications related to the methods and techniques developed during M.Sc. thesis work
(CHI 201401980 and CHI 2015-00297).
* **Management & Project Intern** | GMS Technologies Ltda., Chile (2010-2011)
  * Helped in the design and development of sensor communication projects for the mining industry. Served
as the bridge between Operations and Management teams. Involved with the projects’ high-level design,
technical evaluation, planning, and overseeing their execution on-sit


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Awards
======
* ECE Dissertation Writing Fellowship (2021)
* ECE Advancement-to-Candidacy Fellowship (2019)
* IEEE Teacher Assistant of the Year, IEEE Student Branch, UC Davis (2017-2018)
* Becas Chile Scholarship for Doctorate Studies Abroad (2016-2021)
* Fulbright Chile Scholarship for Graduate Studies in the US (2016-2020)
* Thesis Writing Fellowship (2013)
* Academic Excellence Scholarship, Pontifical Catholic University of Chile (2006)
* Maximum Score in Mathematics, PSU - undergraduate admission exam (2005)
  
Service and Leadership
======
* Candidate for Student Representative at University’s Superior Council, PUC (2010)
* Department of Electrical Engineering Student Representative, PUC (2008 & 2010)
* Chief Coordinator of several volunteering initiatives (2008-2010)
