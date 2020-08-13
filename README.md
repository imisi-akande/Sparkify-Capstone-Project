# Sparkify-Capstone-Project
A project to early detect when a Sparkify user is likely to churn. Check my
blogpost for a detailed analysis.

### Table of Contents
1. [Dependencies](#dependencies)
2. [Motivation](#motivation)
3. [Files Description](#description)
4. [Results](#results)
5. [Acknowledgements](#acknowledgements)

### Dependencies<a name="dependencies"></a>
*Packages needed to implement this project*:

- Python
- Pandas
- Anaconda 3
- Matplotlib
- Seaborn
- PySpark
- Spark
- Python >= 3.7

### Motivation<a name="motivation"></a>

This project aims to tackle one of the most important use cases of Big Data in business - Churn prediction which is a vital tool to retaining customers. It does so by using Apache Spark. The project is a part of the Udacity's Data Scientist Nanodegree program, it involves Sparkify is a fictional music streaming platform created by Udacity similar to Spotify, itunes etc. The dataset contains user behaviour log for the past few months. It contains basic information about the users and specific activities of the users over a period of time.For this project we are given log data of this platform in order to drive insights and create a machine learning pipeline to predict churn. Investigating the reasons of users churn is an interesting and motivating part of the project.

### Files Description<a name="description"></a>
sparkify.ipynb - A notebook with all the preprocessing, feature engineering and modelling.

### Results<a name="results"></a>
Four models were trained on the dataset. The models are Logistic Regression, Random Forest, Support Vector Machines and Gradient Boosted Trees respectively. The models were evaluated and Random Forest outperformed the rest by a large margin in terms of the F1 score plus timely execution. So, Random Forest was selected for improvement by hyper-parameter tuning.

The final metrics for the tuned Random Forest Classifier are as follows:
- The F-1 Score is 0.8499999999999999
- The accuracy is 0.8666666666666667

In the end, the most important features for the prediction of churned users were also selected.

### Acknowledgements<a name="acknowledgements"></a>
I appreciate Udatcity for the project and Data support