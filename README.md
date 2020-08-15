#Using clustering algorithm to segment customers:

#Introduction

Every person is different and so is their behavior as customers.
Imagine you are the owner of a shop. It doesn't matter if you own an e-commerce or a supermarket. It doesn't matter if it is a small shop or a huge company such as Amazon or Netflix, it's better to know your customers.

Machine learning comes in handy for this task. Particularly, clustering, the most important unsupervised learning problem, is able to create categories grouping similar individuals.

These categories are called clusters. A cluster is a collection of points in a dataset. These points are more similar between them than they are to points belonging to other clusters. Distance-based clustering groups the points into some number of clusters such that distances within the cluster should be small while distances between clusters should be large.

Purpose
The goal of this project is to:

Perform an exploratory analysis on the dataset.
Check that the assumptions K-means makes are fulfilled.
Apply K-means clustering algorithm in order to segment customers.
Data Set Information
The csv file corresponding used herein was downloaded from Kaggle repository. The dataset contains data about customers from a Mall. The information gather is: Customer ID, Age, Annual Income (k$), Spending Score (1-100).

Analysis
This repository contains two files:

clustering_analysis.ipybn: In this jupyter notebook, exploratory data analysis is performed. Moreover, the algorithm assumptions are checked. K-means is applied to segment customers obtaining a graph and the customer segments. It is also shown how to predict to which segment a new customers belongs to.
customers.csv dataset used to perform the analysis.
The whole analysis was done using JupyterLab and Python, using libraries such as: pandas, numpy, matplotlib, and scikit-learn.

