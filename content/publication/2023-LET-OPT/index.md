---
title: "Optimizing Logical Execution Time Model for Both Determinism and Low Latency"
date: 2024-03-02
publishDate: 2024-03-02
authors: 
- admin 
- "Dong Li"
- "Ashrarul H Sifat"
- "Shao-yu Huang"
- "Xuanliang Deng"
- "Changhee Jung"
- "Ryan K Williams"
- "Haibo Zeng"
# authors: ["**Sen Wang**", "Dong Li", "Ashrarul H Sifat", "Shaoyu Huang", "Xuanliang Deng",  "Changhee Jung",  "Ryan Williams", "Haibo Zeng"]
# publication_types: ["1"]
abstract: "The Logical Execution Time (LET) programming model has recently received considerable attention, particularly because of its timing and dataflow determinism. In LET, task computation appears always to take the same amount of time (called the task's LET interval), and the task reads (resp. writes) at the beginning (resp. end) of the interval. Compared to other communication mechanisms, such as implicit communication and Dynamic Buffer Protocol (DBP), LET performs worse on many metrics, such as end-to-end latency (including reaction time and data age) and time disparity jitter. Compared with the default LET setting, the flexible LET (fLET) model shrinks the LET interval while still guaranteeing schedulability by introducing the virtual offset to defer the read operation and using the virtual deadline to move up the write operation. Therefore, fLET has the potential to significantly improve the end-to-end timing performance while keeping the benefits of deterministic behavior on timing and dataflow.  

To fully realize the potential of fLET, we consider the problem of optimizing the assignments of its virtual offsets and deadlines. We propose new abstractions to describe the task communication pattern and new optimization algorithms to explore the solution space efficiently. 
The algorithms leverage the linearizability of communication patterns and utilize symbolic operations to achieve efficient optimization while providing a theoretical guarantee. 
The framework supports optimizing multiple performance metrics and guarantees bounded suboptimality when optimizing end-to-end latency.
Experimental results show that our optimization algorithms improve upon the default LET and its existing extensions and significantly outperform implicit communication and DBP in terms of various metrics, such as end-to-end latency, time disparity, and its jitter."
featured: true
publication: "2024 IEEE 30th Real-Time and Embedded Technology and Applications Symposium (**RTAS**)"
links:
  - icon_pack: fas
    icon: scroll
    name: Link
    url: 'https://arxiv.org/abs/2310.19699'
---
