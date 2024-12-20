---
title: "Twister4Azure"
excerpt: "Decentralized Iterative MapReduce For Windows Azure Cloud<br/><img src='/JudyFox/images/azureimage1.png' width='300' height='200'>"
collection: portfolio
---
<img src='/JudyFox/images/azureimage1.png' width='300' height='200'>

Twister4Azure is a distributed decentralized iterative MapReduce runtime for Windows Azure Cloud.

[Website](http://salsahpc.indiana.edu/twister4azure/)

# Introduction

Twister4Azure is a distributed decentralized iterative MapReduce runtime for Windows Azure Cloud that was developed using Azure cloud infrastructure services. Twister4Azure extends MRRoles4Azure by introducing extensions and optimizations for iterative MapReduce applications. Twister4Azure supports caching of loop-invarient data, adds a new merge step (map->reduce->merge) to the programming model and introduces a novel cache-aware task scheduling mechanism.

<img src='/JudyFox/images/azuremodel.png' width='800' height='700'>

Twister4Azure uses Azure Queues for map and reduce task scheduling, Azure Tables for metadata & monitoring data storage, Azure Blob storage for input, output and intermediate data storage and the Window Azure Compute worker roles to perform the computations.  The usage of the cloud infrastructure services allows the Twister4Azure implementation to take advantage of the scalability, high availability and the distributed nature of such services guaranteed by the cloud service providers to avoid single point of failures, bandwidth bottlenecks (network as well as storage bottlenecks) and management overheads.

The usage of cloud services usually introduces latencies larger than their optimized non-cloud counterparts and often does not guarantee the time for the data's first availability. These overheads can be conquered, however, by using a sufficiently coarser grained map and reduce tasks. MapReduceRoles4Azure overcomes the availability issues by retrying and by designing the system so it does not rely on the immediate availability of data to all the workers.

Twister4Azure is designed around a decentralized control model without a master node, thus avoiding the possible single point of failure. MapReduceRoles4Azure provides users with the capability to dynamically scale up or down the number of computing instances, even in the middle of a MapReduce computation, as and when it is needed.

# Publications

**Conferences/Workshops**  
Thilina Gunarathne, Bingjing Zhang, Tak-Lon Wu and Judy Qiu. Scalable Parallel Computing on Clouds Using Twister4Azure Iterative MapReduce, Future Generation Computer Systems(FGCS), Available online 22 June 2012, ISSN 0167-739X, 10.1016/j.future.2012.05.027.(6/2012)

​Gunarathne, T., Wu, T.-L., Choi, J. Y., Bae, S.-H. and Qiu, J. (2011), Cloud computing paradigms for pleasingly parallel biomedical applications. Concurrency and Computation: Practice and Experience. doi: 10.1002/cpe.1780

