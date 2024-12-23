---
title: "IndyCar"
excerpt: "Real-time anomaly detection from edge to HPC-cloud in collaboration with Indycar and Intel.<br/><img src='/JudyFox/images/indycarimage.png' width='300' height='200'>"
collection: portfolio
order: 0
---

## Publications

### Rank Position Forecasting in Car Racing
B. Peng, J. Li, S. Akkas, T. Araki, O. Yoshiyuki, J. Qiu  
Proceedings of 35th IEEE International Parallel & Distributed Processing Symposium (IPDPS21)

### Anomaly Detection Over Streaming Data: Indy500 Case Study
C. Widanage, J. Li, S. Tyagi, R. Teja, B. Peng, S. Kamburugamuve, D. Baum, D. Smith, J. Qiu, and J. Koskey  
2019 IEEE 12th International Conference on Cloud Computing (CLOUD), pp. 9–16, IEEE, 2019.

### A fast video image detection using tensorflow mobile networks for racing cars
S. Akkas and S. S. Maini and J. Qiu  
Stream Systems and Real-time Machine Learning (STREAM-ML) Workshop of IEEE Big Data Conference, IEEE, 2019.

## Objectives

<img src='/JudyFox/images/objectives.png' width='800' height='500'>

## Equipment Malfunction Prediction and Alerts

Anomaly prediction can help engineers identify issues in the hardware before they become serious. Especially at the speed at which these cars travel, small issue can quickly snowball to become catastrophic.

## Recommendations with Evolving Driving Conditions

Track conditions are ever evolving, from humidity, ambient temperature and track temperature. All of these factors affect the way on-board systems perform in different ways. It can be hard for a human to take appropriate action at the appropriate time with such gradual change.

## Performance Tuning During Practice

Performance of hardware can be tuned to minute degrees based on insights provided by AI systems which can go beyond the level of pattern recognition capable by humans.


## Rank Forecasting
Rank position forecasting in car racing is a challenging problem. We propose RankNet, a combination of the encoder-decoder network and a separate Multilayer Perception network that is capable of delivering probabilistic forecasting to model the pit stop events and rank position in car racing. RankNet demonstrates a significant performance improvement.

**Publication**  
Rank Position Forecasting in Car Racing
B. Peng, J. Li, S. Akkas, T. Araki, O. Yoshiyuki, J. Qiu
Proceedings of 35th IEEE International Parallel & Distributed Processing Symposium (IPDPS21) [Link](https://arxiv.org/pdf/2010.01707.pdf)

[Github](https://github.com/DSC-SPIDAL/rankpredictor)

<video src="/JudyFox/images/file.mp4" width="800" height="500" controls></video>


**RankNet Architecture**  
The details of RankNet is shown in our neural network architecture for the two sub-models in Figure.

<img src='/JudyFox/images/ranknetarch.png' width='800' height='500'>


PitModel adopts a simple multilayer perceptron network(MLP), denoted as Stacked Dense layer. RankModel adopts an encoder-decoder architecture, which is widely used in sequence modeling. Both encoder and decoder is a deep neural network capable of modeling long-range context dependencies, such as the classical multi-layer recurrent neural network with LSTM cells, or more recently successful Transformer. A dense layer converts the output of the encoder and decoder into the parameter of a predefined
distribution

**RankNet forecasting results**  
RankNet demonstrates a significant performance improvement, where MAE improves 19% in two laps forecasting task and 7% in the stint forecasting task over the best baseline and is also more stable when adapting to unseen new data. Details of the model optimizations and performance profiling

<img src='/JudyFox/images/rnetfore.png' width='800' height='500'>

RankNet, a combination of the encoder-decoder network and a separate MLP network capable of delivering probabilistic forecasting, to model the pit stop events and rank position in car racing. In this way, we incorporate domain knowledge to enhance the deep learning method.

Our proposed model achieves significantly better accuracy than baseline models in the rank position forecasting task. The advantages of needing fewer feature engineering efforts and providing probabilistic forecasting have enabled us with refined racing strategy optimizations.


## Video Image Detection

A Fast Video Image Detection using TensorFlow Mobile Networks for Racing Cars

**Introduction**  

A Fast Video Image Detection using TensorFlow Mobile Networks for Racing Cars
​
With the growth of the Internet of Things, we see an increase in the importance of analysis of data from the edge, often with the results needed in real-time.

Indy Car series is one of the well-known racing series in North America. All cars are equipped with multiple cameras. The video streams captured by these cameras can be used for detection and predictive tasks to increase race safety and develop better strategies to win the race. Moreover, the data can be used together with the telemetry data to provide better analysis and predictions for the drivers and the teams. In a lot of video analytics tasks, the tasks begin with object detection as its foundation. The existing pretrained object detection models are inadequate to detect IndyCar race cars.

 
Therefore, we have created a new dataset and have compared three different Single Shot Multibox Detector models from TensorFlow Detection Model Zoo. We run experiments on CPU and GPU. Since transferring the data from edge devices to a server, running inference, and sending the result back is time and resource consuming, we also test mobile detection models on an Edge TPU, which is a Google Coral Dev Board. Our initial results show that the Edge TPU gives the best inference time, and it is more suitable for a real-time machine learning task.

<iframe 
src="https://docs.google.com/presentation/d/e/2PACX-1vQGlWVjCg9CBNjiCDzCNMNaPxaUg3sAgFpii81iyXDDxr4A5xR4q4Y-bN7uV_zzPw/embed?start=false&loop=false&delayms=3000"
    frameborder="0"
    width="960"
    height="569"
    allowfullscreen="true"
    mozallowfullscreen="true"
    webkitallowfullscreen="true">
  </iframe>

## Anomaly Detection

Real-time anomaly detection from edge to HPC-cloud in collaboration with Indycar and Intel.

[Github](https://github.com/DSC-SPIDAL/IndyCar)

**Introduction**

With the growth of the Internet of Things, we see an increase in importance of the analysis of data from the edge with often the results needed in real time. Indy Car series is one of the top racing series in North America. All cars are equipped with multiple cameras. The video streams captured by these cameras can be used for detection and predictive tasks to increase race safety, develop better strategies for the teams to win the race. Furthermore, sensor's data can be used as the telemetry data to provide better analysis and predictions for the drivers and the teams.

​

In video image analytics, anomaly detection and prediction tasks start with object detection. We create new datasets and compare three different Single Shot Multibox Detector models from TensorFlow Detection Model Zoo. We run experiments on CPU and GPU, and test mobile detection models on an Edge TPU, which is Google Coral Dev Board. Our initial results show that the Edge TPU gives the best inference time, and it is more suitable for a real-time machine learning task.

**Prototype**


<img src='/JudyFox/images/raceimage1.gif' width='800' height='500'>

<img src='/JudyFox/images/raceimage2.gif' width='800' height='500'>

<img src='/JudyFox/images/raceimage3.gif' width='800' height='500'>