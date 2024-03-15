---
layout: archive
title: "Research"
permalink: /research
author_profile: true
---

{% include base_path %}

This page (under development) summarizes the highlights of my ongoing and past research. More details on a specific work are available in the linked publication.

📅 Last updated: March 14, 2024

<hr style="border: 2px solid #eeeeee;">

# Vehicle Reidentification
### *PhD Dissertation Research (8/2023 - 3/2024)*

<hr style="border: 2px solid #eeeeee;">

# Dilemma Zone Analysis
### *PhD Dissertation Research (1/2023 - 11/2023)*

<hr style="border: 2px solid #eeeeee;">

# Queue Length Estimation
### *PhD Dissertation Research (5/2022 - 7/2022)*

<p align="center" style="margin-bottom: 0;">
  <img src="/images/research/2023_queue estimation.jpg" alt="Queue Length Estimation" style="width: 100%;">
</p>
<p align="center" style="margin-top: 0;">
  <span style="font-size: smaller;">Single-channel advance video detection (left), queueing phenomenon and breakpoints (right)</span>
</p>

- **Objective**: estimate cycle-based maximum queue length in real time using single-channel advance detector data
- **Challenges**
  - volume underestimation with single-channel detection scheme and noisy detection from video sensors
  - arrival information of vehicles not available beyond the advance detector
  - data available from only the advance detector at target intersection
- **Contributions**
  - proposed an estimation methodology based on queuing phenomenon and empirical observation of breakpoints when vehicles pass the advance detector
  - real-time queue estimation with 86% accuracy, obviating the need for manual calibration of threshold parameters
- **Tools used**: R for data processing, analysis, and visualization, [GitHub](https://github.com/prameshpudasaini/queue_estimation)
- **Publication**: **P. Pudasaini**, A. Karimpour, and Y.-J. Wu, “Real-time queue length estimation for signalized intersections using single-channel advance detector data,” *Transportation Research Record*, vol. 2677, no. 7, pp. 144–156, 2023, doi: [10.1177/03611981221151066](https://doi.org/10.1177/03611981221151066).
- **Affiliation**: PhD Student, Center for Applied Transportation Sciences, University of Arizona

<hr style="border: 2px solid #eeeeee;">

# Pre-Disaster Planning of Rural Road Networks
### *Independent Research (6/2020 - 1/2021)*

<p align="center" style="margin-bottom: 0;">
  <img src="/images/research/2020_rural_road_network_redundancy.jpg" alt="Rural Road Network Redundancy" style="width: 100%;">
</p>
<p align="center" style="margin-top: 0;">
  <span style="font-size: smaller;">Study network: Bhimsen Thapa Rural Municipality, Gorkha, Nepal</span>
</p>

- **Objective**: pre-disaster planning and performance evaluation of rural road networks in case of link disruption
- **Contributions**
  - proposed two mathematical metrics for quantifying network redundancy in context of rural roads; metrics are based on the change in total travel distance for rerouting the network traffic when a link fails
  - performed redundancy analysis for a real-world rural road network by implementing Dijkstra's and k-shortest path algorithms in MATLAB
  - developed a decision-support tool for a priori identification of critical road links and maintenance prioritization of existing alternative links
- **Tools used**: MATLAB for implementing shortest path algorithms, Excel for data analysis and visualization, [GitHub](https://github.com/prameshpudasaini/network_redundancy)
- **Publication**: J. K. Shrestha, **P. Pudasaini**, and L. Mussone, “Rural road network performance and pre-disaster planning: an assessment methodology considering redundancy,” *Transportation Planning and Technology*, vol. 44, no. 7, pp. 726–743, 2021, doi: [10.1080/03081060.2021.1956809](https://doi.org/10.1080/03081060.2021.1956809).
- **Affiliation**: Research Assistant, Center for Infrastructure Development Studies, Tribhuvan University

<hr style="border: 2px solid #eeeeee;">

# Optimization of Petroluem Transportation Network
### *Master's Thesis Research (1/2019 - 1/2021)*

<p align="center" style="margin-bottom: 0;">
  <img src="/images/research/2019_petroleum_optimization_II.png" alt="Optimization of Petroleum Transportation Network" style="width: 100%;">
</p>
<p align="center" style="margin-top: 0;">
  <span style="font-size: smaller;">Multi-modal and multi-product shipping pattern for a Pareto optimal solution</span>
</p>

- **Objective**: multi-objective optimization of petroleum transportation network under demand uncertainty
- **Contributions**
  - developed a multi-objective optimization model considering demand stochasticity
  - considered multiple supply centers, distribution centers, products, and transportation modes, along with transshipment between centers
  - formulated optimization model as a mixed-integer linear programming (MILP) problem and solved the model in GAMS
  - generated Pareto optimal solutions to analyze interesting trade-offs between objectives
  - proposed a decision-support tool for strategic (long-term infrastructure setup) and tactical planning (petroleum products' flow allocation) under stochastic demands
- **Tools used**: [GAMS](https://www.gams.com/) for optimization ([code](https://github.com/prameshpudasaini/integrated_dpsc/blob/main/optimization/gams-stochastic.gms)), R for data analysis and visualization, [GitHub](https://github.com/prameshpudasaini/integrated_dpsc)
- **Publication**
  - **P. Pudasaini**, “Integrated planning of downstream petroleum supply chain: a multi-objective stochastic approach,” *Operations Research Perspectives*, vol. 8, p. 100189, 2021, doi: [10.1016/j.orp.2021.100189](https://doi.org/10.1016/j.orp.2021.100189).
  - **P. Pudasaini**, J. K. Shrestha, and R. B. Lopes, “A multi-objective analysis of a petroleum transportation network under uncertainty,” *International Journal of Logistics Systems and Management*, vol. 40, no. 3, pp. 377–395, 2021, doi: [10.1504/IJLSM.2021.120254](https://doi.org/10.1504/IJLSM.2021.120254).
- **Affiliation**: Deputy Manager, Nepal Oil Corporation Limited; Master's Student, Tribhuvan University