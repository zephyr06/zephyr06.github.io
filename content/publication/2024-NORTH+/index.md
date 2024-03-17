---
title: "A General and Scalable Method for Optimizing Real-Time Systems"
date: 2024-01-09
publishDate: 2024-01-09
authors: ["**Sen Wang**", "Dong Li", "Shaoyu Huang", "Xuanliang Deng", "Ashrarul H Sifat",  "Changhee Jung",  "Ryan Williams", "Haibo Zeng"]
publication_types: ["1"]
abstract: "In real-time systems optimization, designers often face a challenging problem posed by the non-convex and non-continuous schedulability conditions, which may even lack an analytical form to understand their properties. To tackle this challenging problem, we treat the schedulability analysis as a black box that only returns true/false results. We propose a general and scalable framework to optimize real-time systems, named Numerical Optimizer with Real-Time Highlight (NORTH). NORTH is built upon the gradient-based active-set methods from the numerical optimization literature but with new methods to manage active constraints for the non-differentiable schedulability constraints. In addition, we also generalize NORTH to NORTH+, to collaboratively optimize certain types of discrete variables (e.g., priority assignments, categorical variables) with continuous variables based on numerical optimization algorithms. We demonstrate the algorithm performance with two example applications: energy minimization based on dynamic voltage and frequency scaling (DVFS), and optimization of control system performance. In these experiments, NORTH achieved 10^2 to 10^5 times speed improvements over state-of-the-art methods while maintaining similar or better solution quality. NORTH+ outperforms NORTH by 30% with similar algorithm scalability. Both NORTH and NORTH+ support black-box schedulability analysis, ensuring broad applicability."
featured: true
publication: "Arxiv"
links:
  - icon_pack: fas
    icon: scroll
    name: Link
    url: 'https://arxiv.org/abs/2401.03284'
---