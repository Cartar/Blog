---
title: "naked statistics"
subtitle: "stripping the dread from the data"
date: 2022-11-14T01:40:14-04:00
tags: ["Books"]
categories: ["Best Books"]
draft: true
---

A masterpiece in fun-reading education; this book is accessible to everyone who's goal is to learn statistics. And for those with a strong handle on the subject, it is a good reminder of the pitfalls of being too brash with the toolkit.

My key takeaways:

### Always check both mean and median
Using one without knowing the other can be dangerous, as both are good at hiding data. Mean can easily hide the distribution, while median hides outliers. Better yet, use both AND include a distribution graph.

### Common biases:
* Selection bias: poorly sampled data skewing results
* Publication bias: omitting negative results via preference for positive news
* Recall bias: our memories suck - or at least they are different than lived experience
* Survivorship bias: what hedge funds do
* healthy user bias: does pills make you healthier or do healthy ppl take pills?

### Central limit theorem (CLT)
The mean of sampled populations will create its own normal distribution, regardless if the population being sampled is normally distributed. The mean of this normal distribution will overlap with the true mean of the population.

The Standard Error (SE) of the sampled means will be proportional to the standard deviation of the underlying population, and the sample number (N).

Review chapter 9 for an elegant example using CLT to infer brain size difference between kids with / without autism. Reviews p-values, SE between 2 means, and one vs two tail hypothesis testing.

### Polling
Polling is an interesting application of statistics in that we can sample a small subset of the entire population, and if done correctly, have a pretty good understanding of the outcome. That is, one must be careful not to accidently introduce a selection bias, and the way in which questions are asked can make a big difference as well.

An aside: SE of polling uses a different formula, which has a maximum variance when the results are 50 / 50.

### Regression analysis
The **regression coefficient** is simply the slope of the line; the residual is the "error" or deviation away from the straight line slope for every dependent variable; independent variables are often called "explanatory", or "control" variables.

The R^2 measures the total amount of variation explained by the regression equation.

Multiple regression analysis is simply a multi-dimensional slope that allows a comparison between explanatory variables to determine how much each variable contributes to the dependent variable. 

### Common regression mistakes
* Using regression for a non-linear relationship
* Correlation does not equal causation
* Reverse causality (B actually causes A, rather than A -> B)
* Omitted variable bias (i.e., missing age when it is in fact the strongest predictor)
* Highly correlated explanatory variables (multicollinearity)
* Extrapolating beyond the data
* Data mining (too many variables)

### Gotchas:
* Assuming events are independent when they're not: i.e., plane engine failures. You'd expect each engine to have an independant probability of failure, but when one fails, it is more likely the second one fails too.

5/5.