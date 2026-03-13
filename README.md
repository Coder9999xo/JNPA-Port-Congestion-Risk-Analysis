
# JNPA Port Congestion Risk Analysis

This project develops a machine learning framework to analyze congestion risk at Jawaharlal Nehru Port Authority (JNPA), India.

The system uses logistic regression to identify congestion risk and diagnose operational causes such as:

- Rail evacuation imbalance
- Export gate congestion
- Operational throughput pressure
- High container demand

## Objective

Modern supply chain prediction models often act as black boxes.  
This project develops a transparent congestion risk analysis framework for port logistics using logistic regression.

The framework aims to:

• predict congestion risk  
• identify operational causes of congestion  
• generate actionable logistics recommendations

## Workflow

Data Cleaning  
Exploratory Data Analysis  
Feature Engineering  
Feature Selection  
Logistic Regression Model  
Cause Analysis  
Recommendation System

![System Architecture](https://quickchart.io/graphviz?graph=digraph%20G%20%7B%20node%20%5Bshape%3Dbox%2C%20style%3D%22rounded%2Cfilled%22%2C%20fillcolor%3D%22%23f6f8fa%22%2C%20color%3D%22%23d0d7de%22%2C%20fontname%3D%22sans-serif%22%5D%3B%20edge%20%5Bcolor%3D%22%2357606a%22%5D%3B%20rankdir%3DTB%3B%20%22Raw%20Data%22%20-%3E%20%22Data%20Cleaning%22%20-%3E%20%22EDA%22%20-%3E%20%22Feature%20Engineering%22%20-%3E%20%22Logistic%20Regression%20Model%22%20-%3E%20%22Cause%20Analysis%22%20-%3E%20%22Recommendation%20Engine%22%20%7D)

## Dataset

Period: Jan 2023 – Dec 2025  
Granularity: Monthly

## Tools

Python  
Pandas  
Scikit-learn  
Matplotlib  
Seaborn

## Model Performance

Baseline Logistic Regression Model

Accuracy: ~0.74  
Recall (Congestion detection): ~0.67  

The model successfully identifies congestion risk and provides interpretable operational drivers through the cause analysis layer.
