---
layout: page
title: Comparing ML/AI models
description: How should we compare models?
img: assets/img/projects/signal_ensemblefig.png
importance: 6
category: work
---

Designing, training, and deploying modern ML/AI models is a very complicated task. If you are given two (or more models), can you tell if they are "functionally the same"? This isn't a well-posed question but it's still important to answer, especially if we want to use the models widely.

The question is easier to ask if we think about a more familiar piece of technology, such as a camera. We might say that two smartphone cameras provide the same functionality while knowing that they are clearly designed and implemented differently. If we want to use images from both cameras for some data analysis, we might need to calibrate to correct for systematic differences.

Asking the same question about ML/AI models leads to a number of different questions about training, model approximations, and model interpretations.

#### Representative publications



#### Talks 

#### Funding

This work was partially supported by the Statistical Inference Generates kNowledge for Artificial Learners (SIGNAL) program at Pacific Northwest National Laboratory (PNNL), as well as by the Mathematics for Artificial Reasoning in Science (MARS) initiative via the Laboratory Directed Research and Development (LDRD) Program at PNNL.

This project was funded by a grant in collaboration with the Pacific Northwest National Labs (PNNL) on trying to understand the variability caused by using stochastic optimization.

Training a deep neural network (DNN) often involves stochastic optimization, which means each run will produce a different model. Several works suggest this variability is negligible when models have the same performance, which in the case of classification is test accuracy. However, models with similar test accuracy may not be computing the same function.

So far we have looked at a new measure of closeness between classification models based on the output of the network before thresholding. Our measure is based on a robust hypothesis-testing framework and can be adapted to other quantities derived from trained models.
