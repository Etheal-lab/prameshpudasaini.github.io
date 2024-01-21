---
layout: archive
title: "Projects & Research"
permalink: /projects
author_profile: true
---

{% include base_path %}

This page summarizes highlights of my ongoing and past projects and research. More details on a specific work are available in the linked final report or research paper.

📅 Last updated: January 21, 2024

# Research: Optimization of Petroleum Transportation Network (Phase II, 2019-20)

<p align="center" style="margin-bottom: 0;">
  <img src="/images/research/2019_petroleum_optimization_II.png" alt="Optimization of Petroleum Transportation Network: Phase II" style="width: 100%;">
</p>
<p align="center" style="margin-top: 0;">
  <span style="font-size: smaller;">Shipping pattern of a Pareto optimal solution under specific demand scenario</span>
</p>

- **Scope**: multi-objective optimization of petroleum transportation network under demand uncertainty
- **Tasks & contributions**
  - developed a multi-objective optimization model considering demand stochasticity
  - considered multiple supply centers, distribution centers, products, and transportation modes, along with transshipment between centers
  - formulated optimization model as a mixed-integer linear programming (MILP) problem and solved the model in GAMS
  - generated Pareto optimal solutions to analyze interesting trade-offs between objectives
  - proposed a decision-support tool for strategic (long-term infrastructure setup) and tactical planning (petroleum products' flow allocation) under stochastic demands
- **Tools used**: [GAMS](https://www.gams.com/) for optimization ([code sample](https://github.com/prameshpudasaini/integrated_dpsc/blob/main/optimization/gams-stochastic.gms)), R for data analysis & visualization
- **Affiliation**: Master's graduate at Tribhuvan University; Deputy Manager at Nepal Oil Corporation Limited
- **Publication**: "Integrated planning of downstream petroleum supply chain: a multi-objective stochastic approach" ([paper link](https://doi.org/10.1016/j.orp.2021.100189))

<hr style="border: 2px solid #eeeeee;">

# Research: Optimization of Petroleum Transportation Network (Phase I, 2019)

<p align="center" style="margin-bottom: 0;">
  <img src="/images/research/2019_petroleum_optimization_I.png" alt="Optimization of Petroleum Transportation Network: Phase I" style="width: 100%;">
</p>
<p align="center" style="margin-top: 0;">
  <span style="font-size: smaller;">Left: comparison of deterministic and stochastic Pareto optimal solutions; Right: cumulative probability distribution of a Pareto optimal solution</span>
</p>

- **Scope**: multi-objective optimization of petroleum transportation network under demand uncertainty
- **Tasks & contributions**
  - developed multi-objective optimization models in deterministic and stochastic settings
  - formulated optimization model as a mixed-integer linear programming (MILP) problem and solved the model in GAMS
  - generated Pareto optimal solutions to analyze trade-offs between objectives
  - proposed a decision-support tool for tactical planning (petroleum products' flow allocation) under deterministic and stochastic demands
- **Tools used**: [GAMS](https://www.gams.com/) for optimization ([code sample](https://github.com/prameshpudasaini/biobjective_petroleum/blob/main/optimization/gams-stochastic-t3.gms)), Excel for data analysis & visualization
- **Affiliation**: Master's student at Tribhuvan University; Deputy Manager at Nepal Oil Corporation Limited
- **Publication**: "A multi-objective analysis of a petroleum transportation network under uncertainty" ([paper link](https://doi.org/10.1504/IJLSM.2021.120254))