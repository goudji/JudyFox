---
title: "Twister"
excerpt: "Iterative Map-Reduce for parallel and scientific computing.<br/><img src='/JudyFox/images/Twister.png' width='100' height='75'>"
collection: portfolio
order: 2
---
<img src='/JudyFox/images/twisterimage1.png' width='100' height='75'>

Build a community to bridge the gap between high performance computing and data analytics.

[Website](https://twister2.org/)

## Introduction
MapReduce programming model has simplified the implementations of many data parallel applications. The simplicity of the programming model and the quality of services provided by many implementations of MapReduce attract a lot of enthusiasm among parallel computing communities. From the years of experience in applying MapReduce programming model to various scientific applications we identified a set of extensions to the programming model and improvements to its architecture that will expand the applicability of MapReduce to more classes of applications. Twister is a lightweight MapReduce runtime we have developed by incorporating these enhancements.

​

Twister provides the following features to support MapReduce computations. (Twister is developed as part of Jaliya Ekanayake's Ph.D. research and is supported by the SALSA Team @ IU)

​

* Distinction on static and variable data

* Configurable long running (cacheable) map/reduce tasks

* Pub/sub messaging based communication/data transfers

* Efficient support for Iterative MapReduce computations (extremely faster than Hadoop or Dryad/DryadLINQ)

* Combine phase to collect all reduce outputs

* Data access via local disks

* Lightweight (~5600 lines of Java code)

* Support for typical MapReduce computations

* Tools to manage data

## Papers and Presentation
Jaliya Ekanayake, Hui Li, Bingjing Zhang, Thilina Gunarathne, Seung-Hee Bae, Judy Qiu, Geoffrey Fox, Twister: A Runtime for Iterative MapReduce," The First International Workshop on MapReduce and its Applications (MAPREDUCE'10) - HPDC2010

 

Jaliya Ekanayake, (Advisor: Geoffrey Fox) Architecture and Performance of Runtime Environments for Data Intensive Scalable Computing, Doctoral Showcase, SuperComputing2009. (Presentation)

 

Jaliya Ekanayake, Atilla Soner Balkir, Thilina Gunarathne, Geoffrey Fox, Christophe Poulain, Nelson Araujo, Roger Barga, DryadLINQ for Scientific Analyses, Fifth IEEE International Conference on e-Science (eScience2009), Oxford, UK.

 

Jaliya Ekanayake, Geoffrey Fox, High Performance Parallel Computing with Clouds and Cloud Technologies, First International Conference on Cloud Computing (CloudComp09) Munich, Germany, 2009.

 

Geoffrey Fox, Seung-Hee Bae, Jaliya Ekanayake, Xiaohong Qiu, and Huapeng Yuan, Parallel Data Mining from Multicore to Cloudy Grids, High Performance Computing and Grids workshop, 2008.

 

Jaliya Ekanayake, Shrideep Pallickara, and Geoffrey Fox MapReduce for Data Intensive Scientific Analysis, Fourth IEEE International Conference on eScience, 2008, pp.277-284.