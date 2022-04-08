# Capstone Project: Beterlsmann/Arvato Custoer Segmentation and Predicting Campaign Response
AWS Machine Learning Engineer Nanodegree <br> Jean Carlos da Cruz

This repository contains code and report for "Beterlsmann/Arvato Custoer Segmentation and Predicting Campaign Response" done as part of Udacity AWS Machine Learning Engineer Nanodegree program Capstone Project.


## Table of Contents

- [Project Overview](#projectoverview)
- [Data Description](#datadescription)
- [Technical Overview](#technicaloverview)
- [Requirements](#requirements)
- [Results](#results)

***

<a id='projectoverview'></a>
## Project Overview

The problem statement can be described as: "Given the demographic data of a person, how can a mail order company convert users into new customers?" In order to answer that question we will first identify segments in the general population and segments inside the existing customers, after that discover what demographic features correspond to a person being a customer for the company. Secondly, we will model a supervised learning algorithm to predict whether a person is a probable customer or not, based on the demographic data.

The project steps can be described as:

1. `Customer Segmentation using Unsupervised Learning`, in this part a thorough data analysis and feature engineering steps are performed to prepare the data for further steps. A Principal Component Analysis (PCA) is performed for dimensionality reduction. Then K-Means Clustering is performed on the PCA components to cluster the general population and the customer population into different segments. These clusters are studied to determine what features make a customer with the help of cluster weights and component weights.

2. `Campaign Response using Supervised Learning`, in this part of the project the customers data with defined targets indicating the past responses of the customers has been used to train Supervised Learning algorithms. Then the trained model is used to make predictions on unseen test data to determine whether a person could be a possible customer.

<a id='datadescription'></a>
## Data Description

The data has been provided by Udacity and Arvato Financial Solutions. The dataset contains 4 data files and 2 description files. The description files have information about the features and their explanation.
The 4 data files include:
* Customer Segmentation
  * General Population demographics
  * Customer demographics
* Customer Acquisition
  * Training data
  * Test data

Per terms and conditions the source datafiles are not provided in this repository since is data provided from Arvato Financial Solutions for this project only purposes and its using is restrict.

<a id='technicaloverview'></a>
## Technical Overview

The project has been divided into various steps which include:
* Domain Background
* Problem Statement
* Dataset and Inputs
* Evaluation Metrics
* Analysis
* Customer Segmentation
* Predicting Campaign Response 
* Results
* References

An explanation about each step has been given in the `Report.pdf`.


<a id='requirements'></a>
## Requirements

* os
* time
* numpy
* pandas
* matplotlib
* seaborn
* sklearn

<a id='results'></a>
## Results
