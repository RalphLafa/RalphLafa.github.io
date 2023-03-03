---
title: Performance Indicator
author: RalphLafa
date: 2023-03-03 21:48:05 +0800
categories: [MachineLearning]
tags: [machinelearning]
math: true
---


## Performance indicator

On regression problem, Root mean square error is generally used as performance indicator

 $$
 RMSE(X,h) = \sqrt{\frac{1}{m}\sum_{i=1}^m (h(x^{(i)} -y^{(i)})^2}
 $$

 -  m is number of sample
 - $x^{i}$  is the entire value of $i_{th}$ feature vectors except label
 - $y^{i}$ is the expected output of label

 
