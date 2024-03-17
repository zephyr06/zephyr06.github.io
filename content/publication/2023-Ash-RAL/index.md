---
title: "A Safety-Performance Metric Enabling Computational Awareness in Autonomous Robots"
date: 2023-06-19
publishDate: 2023-06-19
authors: ["Ashrarul H Sifat", "Xuanliang Deng", "Burhanuddin Bharmal", "**Sen Wang**", "Shaoyu Huang", "Jiabin Huang", "Changhee Jung", "Haibo Zeng", "Ryan Williams"]
publication_types: ["2"]
abstract: "This letter takes a first step towards the analysis of safety and performance critical computational tasks for autonomous robots. Our contribution is a safety-performance (SP) metric that ensures safety first and then rewards improved performance of real-time computational tasks, building on the notion of “nominal safety” which defines timely computation as critical to safety. To fully utilize the computing capacity of heterogeneous processing units (e.g., CPU + GPU), a computational task graph model called the Stochastic Heterogeneous Parallel Directed Acyclic Graph (SHP-DAG) is adopted to capture the uncertain nature of robotic applications and their required computation. Compared to state-of-the-art task models, SHP-DAG avoids the pessimism of deterministic worst-case execution time (WCET), instead modeling the execution times of tasks by probability distributions. Our SP metric is defined upon this task model, which allows us to apply the FIFO and CFS schedulers of the Linux kernel on complex robotic computational tasks and compare the SP metric with baseline metrics, average and worst-case makespan. Extensive experimental results on NVIDIA Jetson AGX Xavier hardware demonstrate that the proposed SP metric is appropriate for managing computational tasks in a manner that balances safety and performance in robotic systems."
featured: true
publication: " 2023 IEEE Robotics and Automation Letters (**RA-L**)"
links:
  - icon_pack: fas
    icon: scroll
    name: Link
    url: 'https://ieeexplore.ieee.org/abstract/document/10197452'
---