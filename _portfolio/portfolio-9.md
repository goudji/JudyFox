---
title: "MapReduceRoles for Azure"
excerpt: "Distributed decentralized MapReduce runtime for Windows Azure<br/><img src='/JudyFox/images/code.png' width='300' height='200'>"
collection: portfolio
---

<img src='/JudyFox/images/code.png' width='300' height='200'>

MapReduceRoles4Azure is a distributed decentralized MapReduce runtime for Windows Azure that was developed using Azure cloud infrastructure services.

[Website](http://salsahpc.indiana.edu/mapreduceroles4azure/)

## Introduction

MapReduceRoles4Azure is a distributed decentralized MapReduce runtime for Windows Azure that was developed using Azure cloud infrastructure services. MapReduceRoles4Azure uses Azure Queues for map and reduce task scheduling, Azure Tables for metadata & monitoring data storage, Azure Blob storage for input, output and intermediate data storage and the Window Azure Compute worker roles to perform the computations.  The usage of the cloud infrastructure services allows the MapReduceRoles4Azure implementation to take advantage of the scalability, high availability and the distributed nature of such services guaranteed by the cloud service providers to avoid single point of failures, bandwidth bottlenecks (network as well as storage bottlenecks) and management overheads.The usage of cloud services usually introduces latencies larger than their optimized non-cloud counterparts and often does not guarantee the time for the data's first availability. These overheads can be conquered, however, by using a sufficiently coarser grained map and reduce tasks. MapReduceRoles4Azure overcomes the availability issues by retrying and by designing the system so it does not rely on the immediate availability of data to all the workers.MapReduceRoles4Azure is designed around a decentralized control model without a master node, thus avoiding the possible single point of failure. MapReduceRoles4Azure provides users with the capability to dynamically scale up or down the number of computing instances, even in the middle of a MapReduce computation, as and when it is needed.

<img src='/JudyFox/images/blob.png' width='600' height='300'>

## Downloads
MapReduceRoles4Azure binary beta version together with few samples is available for download and usage. We are actively working on open sourcing the MapReduceRoles4Azure.

 
1. Visual Studio 2010 is required

2. Install Azure SDK (http://msdn.microsoft.com/en-us/windowsazure/cc974146.aspx)

3. Download MapReduceRoles4Azure library

## Publications

Thilina Gunarathne, Tak-Lon Wu, Judy Qiu, Geoffrey Fox. MapReduce in the Clouds for Science, Proceedings of CloudCom 2010 Conference, IUPUI Conference Center, Indianapolis. November 30-December 3 2010 

 

Thilina Gunarathne (2010), "Azure MapReduce," https://hub.vscse.org/resources/159.
