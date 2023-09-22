---
layout: page
title: Reliability in ML
description: understanding the reliability of ML training 
img: assets/img/signal_ensemblefig
importance: 6
category: work
---

This is a collaboration with the Pacific Northwest National Labs (PNNL) on trying to understand the variability caused by using stochastic optimization.

Training a deep neural network (DNN) often involves stochastic optimization, which means each run will produce a different model. Several works suggest this variability is negligible when models have the same performance, which in the case of classification is test accuracy.  However, models with similar test accuracy may not be computing the same function. 

So far we have looked at a new measure of closeness between classification models based on the output of the network before thresholding. Our measure is based on a robust hypothesis-testing framework and can be adapted to other quantities derived from trained models.
