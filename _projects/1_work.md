---
layout: page
title: Intro. to Statistical Learning
description: A repository created for the class <b>QTM 385 - Statistical Learning</b> at Emory, hosting past ProblemSets, data analysis projects that my group wrote
enable_hyperlink: true
img: assets/img/sl.gif
importance: 1
category: work
github: https://github.com/zejiachen9912/statsticalLearning_QTM385
date: 2022-02-08

toc:
  - name: Introduction
  - name: Project Highlights
    subsections:
       - name: Continuous outcome, Mashable
       - name: Classification, MNIST
       - name: NLP, IMDB
---

## Introduction

This semester-long course covers the basics of Statistical Learning (an essential toolset for making sense of the vast and complex data sets across different industries and fields)

During the class, we learned about a number of important modeling and prediction techniques that are staple to the field of data science and machine learning through the 21st century.

The course pays particular attention to the practical implementation of the various predictive modeling methods, including

1. A review of probability theory and an introduction to MLE
  - Probability theory review, Bayes' rule, Maximum Likelihood Estimation
  - a brief discussion about model fitting, model comparison, and predictive accuracy,

2. Regression as a predictive task and general model fitting
  - A review on linear and multiple linear regression,
  - alternative prediction methods for continuous outcomes:
    sparse regression (Ridge, LASSO, and Elastic Net), non-linear methods (splines), tree-based methods
  - Modeling fitting: cross validation and leave-one-out cross validation, bootstrapping

3. Classification methods
  - Discrete classification method: logistic
  - Generative classification approaches: naïve Bayes, LDA, QDA
  - SVD & flexible classification methods (K-nearest neighbors, ensembles)

4. Unsupervised methods
  - Clustering (K-Centroid Clustering, Generative Clustering, Hierarchical Clustering)
  - Principal components analysis & Matrix Completion
  - Semi-supervised methods

*This class is also the first class ever that I try to use Github to collaborate across my team. I learned a lot not only out of the course material but also team collaboration and task management.*

---

## Project Highlights

#### Continuous outcome, Mashable

In this project, my group attempts to understand and predict what Mashable (a renowned digital publisher) articles are most likely to to garner the most shares. Our goal is to built a continuous outcome model to truthfully predict the log number of shares for an article on Mashable dataset. (35000 observation & 59 covariates)

My group built three disparate models with the fist one aiming at minimizing the expected prediction error on the unseen test set, the second one using a subset (5) of predictors, and the third one picking only one big predictor to complete our model selection task.

For more detail, visit [here](https://github.com/zejiachen9912/statsticalLearning_QTM385/tree/main/midterm1/Midterm)


#### Classification, MNIST

In this project, we tested and eventually selected three classification models for classifying 2-class, 3-class, and 10-class digits in the [MNIST data set](https://en.wikipedia.org/wiki/MNIST_database) separately.

For a project write-up and outcome, visit [here](https://htmlpreview.github.io/?https://github.com/zejiachen9912/statsticalLearning_QTM385/blob/main/DataAnalysis%232/Midterm2_Finalized/Midterm2_Finalized.html)

#### NLP, IMDB

Conduct a sentimental analysis on IMDB film review data set, striving to build the best classification model distinguishing positive and negative film reviews using BERT and logistic regression.

For the complete write-up and source code, visit [here](https://github.com/zejiachen9912/statsticalLearning_QTM385/tree/main/FinalProject)
