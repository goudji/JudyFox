---
title: "NEC Vector Engine"
excerpt: "Leverage the leading-edge vector technology of SX-Aurora TSUBASA<br/><img src='/JudyFox/images/NECimg.png' width='300' height='200'>"
collection: portfolio
---
<img src='/JudyFox/images/NECimg.png' width='300' height='200'>

[Github](https://github.com/dsc-nec/frovedis_matrix)

## Introduction

The NEC Vector Engine Processor have eight independent vector cores. There are 64 fully functional vector registers per core, which can feed the functional units or which receive results from those. The Vector Engine Processor has the world's first implementation of one processor with six HBM2 memory modules using Chip-on-Wafer-on-Substrate technology, leading to the world-record memory bandwidth of 1.2 TB/s.

<img src='/JudyFox/images/vector.png' width='800' height='400'>

We demonstrate significant initial work of Generalized Sparse Matrix-Matrix Multiplication(SpGEMM) kernel for a vector engine. We propose a SpGEMM algorithm with a novel hybrid method based on sparse vectors and loop raking to maximize the length of vectorizable code for vector machine architectures.

NEC SpGEMM has an average performance improvement of 139% over CPU and up to 6.43x performance improvement. The experimental results show that the vector engine has advantages on more massive data sets. This work contributes to the high performance and portability of the SpGEMM kernel to a new family of heterogeneous computing systems, which is Vector Host (VH) equipped with different accelerators or VEs.

**Performance Evaluation**  

<img src='/JudyFox/images/NECGraph.png' width='800' height='400'>

We compare NEC-Hybrid SpGEMM with Intel MKL. The performance is evaluated by claculating A^2. The FLOPS is calculated as
(the number of non-zero of intermediate sparse vectors) * 2 /(execution time), which is commonly used as SpGEMM evaluation. The execution time does not contain I/O but contains the counting cost for load balancing.

NEC-Hybrid has an average performance improvement of 139% over CPU, with a maximum performance improvement of 6.43x. Moreover, the improvement of 2 sockets over 1 socket indicates that the vector machine has better scalability.

## Publications

B. Peng, J. Li, S. Akkas, T. Araki, O. Yoshiyuki, J. Qiu, "Rank Position Forecasting in Car Racing",  Proceedings of 35th IEEE International Parallel & Distributed Processing Symposium (IPDPS21)

​

J. Li, F. Wang, and Q. J. Araki, Takuya, “Generalized sparse matrix-matrix multiplication for vector engines and graph applications,” in
MCHPC’19: Workshop on Memory Centric High Performance Computing, ACM, 2019.

