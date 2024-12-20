---
title: "Intel High Performance Data Analytics"
excerpt: "Innovative convergence solutions in high performance data analytics and simulation software development using Intel architecture.<br/><img src='/images/500x300.png'>"
collection: portfolio
---

## SubGraph2Vec Vectorized Tree-like Subgraph Counting

Subgraph counting aims to count occurrences of a template T in a given network G(V, E). It is a powerful graph analysis tool and has found real-world applications in diverse domains.

 

Scaling subgraph counting problems is known to be memory bounded and computationally challenging with exponential complexity.

 

Challenges of Subgraph Counting:

* Extremely high computational complexity. counting the exact number of subgraphs of size k in a n-vertex network takes O(n^k)time. Approximate  algorithm has a time complexity linear in network size, it is exponential to subgraph size.

* Memory Access Efficiency. Graph Analytics algorithms usually have irregular and intensive random memory access, which is harmful to efficient cache prefetching.

* SIMD Efficiency. Recent many-core architectures such as Intel Xeon Phi have “Vector processing units” (VPU), which only support SIMD programming mode, while graph analytics algorithms are difficult to be vectorized.

​

Our Approach:

* Algorithmic Design: We convert the sequential color-coding algorithm to matrix operations.

* System design and optimization. We design a data structure as well as a thread execution model to leverage the hardware efficiency of using linear-algebra kernels in terms of vector processing units (VPU) and memory bandwidth.

* Portability to the distributed system and GPU. We scale out our single node implementation on a distributed system with near-linear strong scalability. In addition, we export the codes to NVIDIA GPU and NEC Vector Engine

​

We propose a novel vectorized subgraph counting algorithm, named Subgraph2Vec, as well as both shared memory and distributed implementations:

* Reducing algorithmic complexity by minimizing neighbor traversal;

* Achieving a highly-vectorized implementation upon linear algebra kernels to significantly improve performance and hardware utilization.

* Subgraph2Vec improves the overall performance over the state-of-the-art work by orders of magnitude and up to 660x on a single node.

* Subgraph2Vec in distributed mode can scale up the template size to 20 and maintain good strong scalability.

* Enabling portability to both CPU and GPU.

## Publications

L.  Chen,  J.  Li,  C.  Sahinalp,  M.  Marathe,  A.  Vullikanti,  A.  Nikolaev, E.  Smirnov,  R.  Israfilov,  and  J.  Qiu,  “Subgraph2vec:   Highly-vectorized tree-like  subgraph  counting,”  in 2019 IEEE International Conference on Big Data, IEEE, 2019.

 

L. Chen, J.  Li , A. Azad, L. Jiang, A.  Vullikanti,  A.  Nikolaev, E.  Smirnov,  R.  Israfilov,  and  J.  Qiu,  "A GraphBLAS Approach for Subgraph Counting," arXiv preprint arXiv:1903.04395.


