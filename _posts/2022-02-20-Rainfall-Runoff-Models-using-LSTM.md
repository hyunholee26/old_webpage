---
title: "Rainfall Runoff Models using LSTM"
tags: 
  - Graph Neural Network
toc: true
toc_sticky: true
---

## 1. [Rainfall–runoff modelling using Long Short-Term Memory (LSTM) networks](https://hess.copernicus.org/articles/22/6005/2018/)
 - Authors : Frederik Kratzert, Daniel Klotz, Claire Brenner, Karsten Schulz, and Mathew Herrnegger
 - Abstract : Rainfall–runoff modelling is one of the key challenges in the field of hydrology. Various approaches exist, ranging from physically based over conceptual to fully data-driven models. In this paper, we propose a novel data-driven approach, using the Long Short-Term Memory (LSTM) network, a special type of recurrent neural network. The advantage of the LSTM is its ability to learn long-term dependencies between the provided input and output of the network, which are essential for modelling storage effects in e.g. catchments with snow influence. We use 241 catchments of the freely available CAMELS data set to test our approach and also compare the results to the well-known Sacramento Soil Moisture Accounting Model (SAC-SMA) coupled with the Snow-17 snow routine. We also show the potential of the LSTM as a regional hydrological model in which one model predicts the discharge for a variety of catchments. In our last experiment, we show the possibility to transfer process understanding, learned at regional scale, to individual catchments and thereby increasing model performance when compared to a LSTM trained only on the data of single catchments. Using this approach, we were able to achieve better model performance as the SAC-SMA + Snow-17, which underlines the potential of the LSTM for hydrological modelling applications.
 - Noteworthy parts : Figure 15 shows the evolution of a single LSTM cell (ct; see Sect. 2.1) of a trained LSTM over the period of one input sequence (which equals 365 days in this study) for an arbitrary, snow-influenced catchment. **We can see that the cell state matches the dynamics of the temperature curves, as well as our understanding of snow accumulation and snowmelt. As soon as temperatures fall below 0 ∘C the cell state starts to increase (around time step 60) until the minimum temperature increases above the freezing point (around time step 200) and the cell state depletes quickly.** Also, the fluctuations between time steps 60 and 120 match the fluctuations visible in the temperature around the freezing point. Thus, albeit the LSTM was only trained to predict runoff from meteorological observations, it has learned to model snow dynamics without any forcing to do so.

<p align="center"><img src="https://hess.copernicus.org/articles/22/6005/2018/hess-22-6005-2018-f15-thumb.png"></p>
