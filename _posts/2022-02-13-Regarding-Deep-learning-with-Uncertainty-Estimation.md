---
title: "Regarding Deep learning with Uncertainty Estimation"
tags: 
  - uncertainty estimation
toc: true
toc_sticky: true
---
I will summarize serveral articles regarding deep learning with uncertainty estimation. Providing confidence intervals in regression problems is related to uncertainty estimation. A phrase that can express this well is quoted as follows.

> We do a lot of regression, with everything from random forests to recurrent neural networks. And as good as our models are, we know they can never be perfect. Therefore, whenever we provide our customers with predictions, we also like to include a set of confidence intervals: what range around the prediction will the actual value fall within, with (e.g.) 80% confidence?

## 1. [A guide to generating probability distributions with neural networks](https://medium.com/hal24k-techblog/a-guide-to-generating-probability-distributions-with-neural-networks-ffc4efacd6a4)
 - This article give the example code related to generate distribution of predicted value with cumstomed layer and loss function.

## 2. [How to generate neural network confidence intervals with Keras](https://medium.com/hal24k-techblog/how-to-generate-neural-network-confidence-intervals-with-keras-e4c0b78ebbdf)
 - This article suggests same notion and implementation with [Monte Carlo Dropout](https://towardsdatascience.com/monte-carlo-dropout-7fd52f8b6571). Also, it gives the way to calculate optimal dropout rate.


