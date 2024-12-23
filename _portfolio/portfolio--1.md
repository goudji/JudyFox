---
title: "Covid Prediction"
excerpt: "Interpreting County Level COVID-19 Infection and
Feature Sensitivity using DL Time Series Models<br/><img src='/JudyFox/images/covid.png' width='300' height='200'>"
collection: portfolio
order: 0
---

<img src='/JudyFox/images/covid.png' width='300' height='200'>

Funded by NSF Expedition grant

[Github](https://github.com/Data-ScienceHub/gpce-covid)

## Introduction

Interpretable machine learning plays a key role in healthcare. In this work, we propose a novel framework that combines sensitivity analysis with heterogeneous time-series deep learning model prediction, which corresponds to these interpretations of spatio-temporal features, with what the model has actually learned from. We study how deep learning models forecast COVID-19 infection in cases using the Temporal Fusion Transformer (TFT) from Google. We then use sensitivity analysis combined with the Morris Method to see how sensitive the output is with respect to perturbation to our input features.

 

The significance of the work is grounded in a non-trivial real-world county-level COVID-19 cases prediction with highly dynamic,
fine-grained and heterogeneous data. Our modified TFT model can capture the detailed daily changes of temporal and spatial model behaviors and achieves high prediction accuracy compared to the baseline Pytorch model. By correlating the Morris index with attention patterns, we can decipher the meaning of feature importance with observational population and dynamic model changes.

 

We have collected a large number of socioeconomic and health features over 3142 counties, such as observed cases and deaths, and a number of static (age distribution, health disparity, and industry) and dynamic features (vaccination, disease spread, transmissible cases, and social distancing). Using the proposed framework, we show our model can learn complex interactions and perform predictions in all counties in the US, and shed light on individual feature interpretation via sensitivity analysis. Being able to model the disease infection with both prediction and description accuracy at a county level allows administrators to make effective mitigation and responses for the future.​

## Publications

Interpreting County-Level COVID-19 Infections using Transformer and Deep Learning Time Series Models 
Khairul Islam, Di Zhu, Yingzheng Liu, Andrej Erkelens, Nick Daniello, Aparna Marathe, Judy Fox 
Proceedings of the IEEE Conference on Digital Health (ICDH 2023), July 2-8, 2023, Chicago.

## References

Secondary industry segments
Us Census Bureau, North American Industry Classification System(naics) 2017 Paperbound, ser. North American IndustryClassification System. Claitor’s Publishing Division, 2017. 