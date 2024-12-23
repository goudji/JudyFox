---
title: "IndexedHBase"
excerpt: "Customizable indexing framework to support fast queries and analysis of interesting data subsets<br/><img src='/JudyFox/images/indexbase.png' width='300' height='200'>"
collection: portfolio
order: 4
---

<img src='/JudyFox/images/indexbase.png' width='300' height='200'>

Customizable indexing framework to support fast queries and analysis of interesting data subsets
IndexedHBase can achieve a query evaluation speed that is siginifcantly faster than using the existing indexing techniques provided by commercial NoSQL databases.

[Website](http://salsaproj.indiana.edu/IndexedHBase/index.html)

## Introduction

**What is IndexedHBase?**  

As data intensive problems evolve, many research projects require efficient analysis of a target subset of data, rather than the whole data set. IndexedHBase is a storage system that extends HBase with a customizable indexing framework to support fast queries and analysis of interesting data subsets. Leveraging an architecture based on YARN, IndexedHBase can be integrated with various parallel computing platforms, such as Hadoop MapReduce and Twister, to complete efficient analysis of the query results.

**What can IndexedHBase do?**  

By building index structures that are specially customized for the actual applications, IndexedHBase can achieve a query evaluation speed that is siginifcantly faster (by one to two orders of magnitudes) than using the existing indexing techniques provided by commercial NoSQL databases such as Riak.

 

IndexedHBase has been successfully used in several applications, including Text Indexing (with ClueWeb09), LCIR Synonym Mining, and Social Data Analysis (with Twitter data sets). Please check out our System Design and Publications for more details.

## Publications

**Conferences/Workshops**  

Gao, X., Emilio Ferrara, Judy Qiu. Parallel Clustering of High-Dimensional Social Media Data Streams. In Proceedings of the 15th IEEE/ACM International Symposium on Cluster, Cloud and Grid Computing (CCGrid 2015). Shenzhen, Guangdong, China, May 4-7, 2015.​

 

Gao, X., Qiu. J. 2014. Supporting Queries and Analyses of Large-Scale Social Media Data with Customizable and Scalable Indexing Techniques over NoSQL Databases. In Proceedings of the 14th IEEE/ACM International Symposium on Cluster, Cloud and Grid Computing (CCGrid 2014). Chicago, IL, USA, May 26-29, 2014.

 

Gao, X., Qiu. J. 2013. Social Media Data Analysis with IndexedHBase and Iterative MapReduce. In Proceedings of the 6th Workshop on Many-Task Computing on Clouds, Grids, and Supercomputers (MTAGS 2013) at Super Computing 2013. Denver, CO, USA, November 17th, 2013.

 

Gao, X., Roth, E., McKelvey, K., Davis, C., Younge, A., Ferrara, E., Menczer, F., Qiu, J. 2013. Supporting a Social Media Observatory with Customizable Index Structures - Architecture and Performance. Book chapter to appear in Cloud Computing for Data Intensive Applications, to be published by Springer Publisher, 2014.

 

Gao, X., Nachankar, V., Qiu. J. 2011. Experimenting Lucene Index on HBase in an HPC Environment. In Proceedings of the 1st workshop on High-Performance Computing meets Databases at Supercomputing 2011. Seattle, WA, USA, November 18, 2011.