---
layout: page
title: "Research"
---
My research area is global sensitivity analysis (GSA), a subfield of uncertainty quantification. We use GSA to identify which parameters or inputs have the most influence over the output of a model. It is a tool seeing growing use across mathematics and science. GSA can help researchers better understand the structure of complicated black box models, such as deep neural networks or biological mechanistic models). My projects focus both on methods and applications of GSA. 

### Surrogate-assisted global sensitivity analysis

Black box models often come with large computational expense. In these cases, it makes more sense to work with a surrogate model instead. This process introduces two sources of error in the global sensitivity analysis. The first one is due to the approximation error of the surrogate and the second one due to the error in estimating the surrogate’s sensitivity indices. Sampling of the surrogate is often considerably cheaper than sampling the underlying model. However, this sampling can still be costly. In the best case, we can derive analytic formulas for the surrogate model.

### Global sensitivity analysis of Bayesian inverse problems

When researchers want to make predictions about the spread of an epidemic or about the trajectory of a hurricane, they have a model framework to describe these dynamics. However, they do not know which model parameters will reproduce their observations. An inverse problem is one where we hope to find those model parameters, and therefore the entirety of the dynamics, from the observations we have. Since data collection involves some measurement noise, it is important to estimate the uncertainty of our predictions. This motivates the Bayesian framework where model parameters are treated as random variables. 
