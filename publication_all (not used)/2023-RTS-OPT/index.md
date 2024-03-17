---
title: "A General and Scalable Method for Optimizing Real-Time Systems with Continuous Variables"
date: 2023-05-12
publishDate: 2023-6-23
authors: 
- admin 
- "Ryan K Williams"
- "Haibo Zeng"
# publication_types: ["1"]
abstract: "In the optimization of real-time systems, designers often face a challenging problem where the schedulability conditions are non-convex, non-continuous, or lack an analytical form to understand their properties. In this paper, we propose a general and scalable framework for optimizing real-time systems, named Numerical optimizer with Real-Time Highlight (NORTH). NORTH treats schedulability analysis as a blackbox which may only return true/false results on system schedulability. Built upon the active-set methods from the gradient-based numerical optimization literature, NORTH proposes new methods to manage active constraints to further improve the gradient-based optimizers. We apply the proposed approach to two example problems, one on energy optimization for systems with dynamic voltage and frequency scaling, and the other on the optimization of control performance. Experimental results demonstrate that the proposed framework runs 10 2 to 10 5 times faster than state-of-the-art methods while maintaining similar solution quality."
featured: true
publication: "2023 IEEE 29th Real-Time and Embedded Technology and Applications Symposium (**RTAS**)"
links:
  - icon_pack: fas
    icon: scroll
    name: Link
    url: 'https://ieeexplore.ieee.org/abstract/document/10155685'
  - icon_pack: ai
    icon: open-data
    name: Open-source
    url: 'https://github.com/zephyr06/RT_System_Design_Numerical_Methods'
---