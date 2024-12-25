---
title: "Harp"
excerpt: "High Performance Machine Learning tools for achieving your goals faster.<br/><img src='/JudyFox/images/Harpimage.png' width='100' height='75'>"
collection: portfolio
order: 1
---

<img src='/JudyFox/images/Harpimage.png' width='100' height='75'>

[Website](https://dsc-spidal.github.io/harp/) [GitHub](https://github.com/DSC-SPIDAL/harp)
## Introduction


Harp is a HPC-ABDS (High Performance Computing Enhanced Apache Big Data Stack) framework aiming to provide distributed machine learning and other data intensive applications.

​

Recent newly designed Big Data processing tools focus on the abstraction of data and related computation flows. For example, Hadoop MapReduce defines data as Key-Value pairs and computation as Map-Reduce tasks. Pregel/Giraph perceives data as vertices and edges in graphs and computation as BSP iterations. Spark abstracts data as RDDs with transformation operations on top of them. However, there is no abstraction of communication patterns in these tools. On the other hand, traditional distributed data processing tools, represented by MPI, have abstraction of collective communication. But this kind of abstraction is limited because it is only based on arrays and buffers. It cannot support complicated data abstractions and related communication patterns such as shuffling on Key-Values or graph communication based on edges and vertices.

​

To improve the expressiveness and performance in big data processing, the Harp library is introduced, which provides data abstractions and related communication abstractions and transforms map-reduce programming models into map-collective models. The word “harp” symbolizes the effort to make parallel processes cooperate together through collective communication for efficient data processing, just as strings in a harp can make concordant sound. Harp can integrate with Hadoop 1.2.1 and Hadoop 2.2.0. It supports data abstraction types such as arrays, key-values, and graphs with related collective communication operations on top of each type. Several applications are developed based on Harp framework, including K-means clustering, multi-dimensional scaling and PageRank. Being based on Hadoop, Harp has better sustainability and fault tolerance properties than Twister or Twister4Azure that inspired it.

## Partners
![alt text](/JudyFox/images/partnersHARP.png)

## Publications

**Conferences/Workshops**  
Chen L., Li J., Sahinalp C.,Marathe M.,  Vullikanti A. , Nikolaev A., Smirnov E., Israfilov R., and Qiu J., SubGraph2Vec: Highly-Vectorized Tree-like Subgraph Counting, 2019 IEEE Big Data (Acceptance rate 19%), Los Angeles, CA, December 9-12, 2019

Li J., Wang F., Araki T., Qiu J., Generalized Sparse Matrix-Matrix Multiplication for Vector Engines and Graph Applications, Memory Centric High Performance Computing (MCHPC'19) of SC'19 conference, Denvor, Colorado, November 18, 2019

Peng B., Chen L., Li J.,  Jiang M.,  Akkas S.,  Smirnov E., Israfilov R., Khekhnev S.,  Nikolaev A., and Qiu J., HarpGBDT: Optimizing Gradient Boosting Decision Tree for Parallel Efficiency, IEEE Cluster Conference 2019 (Acceptance rate 20%), Albuquerque, New Mexico, September 24-26, 2019.

Jiang, L., Chen, L. and Qiu, J., 2018, April. Performance characterization of multi-threaded graph processing applications on many-integrated-core architecture. In 2018 IEEE International Symposium on Performance Analysis of Systems and Software (ISPASS) (pp. 199-208). IEEE.

Peng, B., Zhang, B., Chen, L., Avram, M., Henschel, R., Stewart, C., Zhu, S., Mccallum, E., Smith, L., Zahniser, T. and Omer, J., 2017, December. HarpLDA+: Optimizing latent dirichlet allocation for parallel efficiency. In 2017 IEEE International Conference on Big Data (Big Data) (pp. 243-252). IEEE.

Chen, L., Peng, B., Zhang, B., Liu, T., Zou, Y., Jiang, L., Henschel, R., Stewart, C., Zhang, Z., Mccallum, E. and Tom, Z., 2017, June. Benchmarking Harp-DAAL: High performance hadoop on KNL clusters. In 2017 IEEE 10th International Conference on Cloud Computing (CLOUD) (pp. 82-89). IEEE.

Zhang, B., Peng, B. and Qiu, J., 2016, June. Model-centric computation abstractions in machine learning applications. In Proceedings of the 3rd ACM SIGMOD Workshop on Algorithms and Systems for MapReduce and Beyond (p. 3). ACM.

Zhang, B., Peng, B. and Qiu, J., 2016. High performance lda through collective model communication optimization. Procedia Computer Science, 80, pp.86-97.

Fox, G.C., Qiu, J., Kamburugamuve, S., Jha, S. and Luckow, A., 2015, May. Hpc-abds high performance computing enhanced apache big data stack. In 2015 15th IEEE/ACM International Symposium on Cluster, Cloud and Grid Computing (pp. 1057-1066). IEEE.

Jha, S., Qiu, J., Luckow, A., Mantha, P. and Fox, G.C., 2014, June. A tale of two data-intensive paradigms: Applications, abstractions, and architectures. In 2014 IEEE International Congress on Big Data (pp. 645-652). IEEE. (IEEE BigData 2014: acceptance rate 19%).

Zhang, B., Ruan, Y. and Qiu, J., 2015, March. Harp: Collective communication on hadoop. In 2015 IEEE International Conference on Cloud Engineering (pp. 228-233). IEEE.

Qiu, J., Jha, S., Luckow, A. and Fox, G.C., 2014. Towards HPC-ABDS: an initial high-performance big data stack. Building Robust Big Data Ecosystem ISO/IEC JTC, 1, pp.18-21.

Wu, T.L., Koppula, A. and Qiu, J., 2014, November. Integrating Pig with Harp to support iterative applications with fast cache and customized communication. In Proceedings of the 5th International Workshop on Data-Intensive Computing in the Clouds (pp. 33-39). IEEE Press.

**Books**  
Chen L., Peng B. , Ossen S. , Vullikanti A., Marathe M. , Jiang L.  and Qiu J., High-Performance Massive Subgraph Counting using Pipelined Adaptive-Group Communication. Book Series of “HPC and Big Data: Convergence and Ecosystem”, pp173-197, IOS Press, 2018.  Doi: 10.3233/978-1-61499-882-2-173.

Zhang B. , Peng B. , Qiu J. . Parallelizing Big Data Machine Learning Parallelizing Big Data Machine Learning, book series on Advances in Parallel Computing published by IOS Press, 2016.

Wu T. , Zhang B. , Davis C. , Ferrara E. , Flammini S. , Menczer F. , Qiu J. , “Scalable Query and Analysis for Social Networks: An Integrated High-Level Dataflow System with Pig and Harp”, Book chapter to be published in Big Data in Complex and Social Networks handbook, CRC Press, Taylor & Francis Group, 2016.

Fox G. , Qiu J. , Jha S. , Ekanayake S. , Kamburugamuve S. , “Big Data, Simulations and HPC Convergence”. Workshop on Big data Benchmarks (WBDB), pp. 3-17, Lecture Notes in Computer Science Book Series (LNCS, Volum3 10044), Springer publisher. 2015.

**Journals**
Zhao, Z., Chen, L., Avram, M., Li, M., Wang, G., Butt, A., Khan, M., Marathe, M., Qiu, J. and Vullikanti, A., 2017. Finding and counting tree-like subgraphs using MapReduce. IEEE Transactions on Multi-Scale Computing Systems, 4(3), pp.217-230. 
