---
title: "SGX-based Big-Data Analytics Frameworks"
excerpt: "Scalable big-data analytics frameworks over the SGX TEE to support iterative, MPI-based cluster computing<br/><img src='/images/500x300.png'>"
collection: portfolio
---

## Introduction

Intel® Software Guard Extensions (Intel® SGX) is a set of instructions that increases the security of application code and data, giving them more protection from disclosure or modification. Developers can partition sensitive information into enclaves, which are areas of execution in memory with more security protection.

​

We develop scalable big-data analytics frameworks over the SGX TEE to support iterative, MPI-based cluster computing. An example of the framework that could be enhanced over the SGX platform is HARP-DAAL. Our secure framework will be designed to address unique performance and security challenges introduced by the SGX hardware. It will support complicated data and communication abstractions for machine learning. Further we will build a novel hybrid model, allowing part of computation performed outside enclaves, when it only involves public data.

​

We plan to build a new framework for SGX-enabled systems, called PROBIDA (Protected Big-Data Analytics). PROBIDA can be built on Harp-DAAL and will be designed to leave the scheduler and other management components outside enclaves but keeps key computing components (workers such as combiners, mapper, etc.) inside the protection perimeter, given our objective for protecting data. It will support various performance enhancement techniques, allowing multiple nodes inside the same enclave and strategic deployment of enclaves and nodes, depending on the computing needs and resource constraints. More specifically, PROBIDA will include a set of building blocks for securely creating enclaves, running attestations across enclaves and establishing secure connections between enclaves. On top of them, our framework will provide a computing task formation tool, which automatically translates the task graph and computing resources specified by the user into a deployment by solving the aforementioned optimization problem, and automatically generates nodes, enclaves and connections according to the deployment over SGX-enable cloud hosts for running a given task.

## Publications

**Conferences/Workshops**  

