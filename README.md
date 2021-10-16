# Customer Segmentation and Acquisition - Bertelsmann Arvato
Data Scientist Udacity Nanodegree - Capstone Project </BR> 
--------------------------------------------------------------
This repository contains code for "Capstone Project - Arvato Customer Segmentation" done as part of Data Scientist Udacity Nanodegree program.

## Table of Contents
* Project Overview
* Data Description
* Technical Overview
* Requirements

### Data Description:
The data has been provided by Udacity and Arvato Financial Solutions. The dataset contains 4 data files and 2 description files. The description files have information about the features and their explanation. The 4 data files include:

* Customer Segmentation
    * General Population demographics
    * Customer demographics
* Customer Acquisition
    * Training data
    * Test data
   
### Technical overview:
Step by step workflow from data exploration, processing to inference is approached in a structured fashion. Code is written using functions tp remove unnecessary data and outliers and implement dimensionality Reduction and Clustering to identify segments. Due to the nature of the data (details in notebook), AUC/ROC is used as the evaluation metric for this project. Prediction for test set is to be submitted to Kaggle competition for evaluation.

Following concepts implemented and covered in detail in the notebook:

* Data Exploration & Cleansing
* Dimensionality Reduction
* Clustering
* Supervised Learning
* Final Model Evaluation
* Feature Importance
* Analysis of identified important features in clusters to find relevance
* Scoring and submisstion to Kaggle

### Requirements:
All of the requirements are captured in requirements.txt. Run: pip install -r requirements.txt
