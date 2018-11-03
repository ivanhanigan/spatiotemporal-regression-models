---
layout: default
title: README
---



This is an Open Notebook (Licence CC-BY-4.0) with some material from other sites (attributed).

In this notebook we will introduce what multi-level data and models are and why they are useful in epidemiology contexts. 

A secure online Rstudio server (in a web browser) is available at [https://rstudio.coesra.org.au](https://rstudio.coesra.org.au) hosted by Uni Queensland's [Collaborative Environment for Ecosystem Science Research and Analysis - CoESRA](http://www.coesra.org.au).

We begin with the general linear model framework GLM and then move to mixed-effects models. It is important to realise that these models are called different things in different disciplines: (generalized) linear mixed (effects) models (GLMM), hierarchical (generalized) linear models, etc. The terminology for the model parameters is equally diverse, usually including the terms random effects and fixed effects. So we focus on the key concepts.

We will cover what is a Random Effect and how it differs from a Fixed effect. Some example syntax in R and Stata will show how to get a handle on models that have random intercepts and additionally, random slopes.

We will spend a little time talking about how to partition variation and get estimates of the random and fixed effects. An important element will be our discussion of similarities between mixed-effects models with basic regression. There will also be brief discussion of extending the regression to non-gaussian responses (GLMERs).

We will discuss how to interpret these results in a population health context.