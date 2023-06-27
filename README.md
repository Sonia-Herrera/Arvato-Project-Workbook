# Arvato Financial Solutions Customer Segmentation Report

## 📝Table of Contents 
* Project Description
* Installation
* File Descriptions
* Blog
* Licensing, Authors, Acknowledgements

## 🗒️Project Description
The goal of this project is to predict which people are most likely to become customers of Arvato Financial Services, a German company. It is based on an analysis of customer demographics compared to the demographic information of the general population in Germany.
The above analysis will be used to predict which individuals will respond to the marketing campaign so that the company can target them rather than the entire population. 

The goal of the project is to predict whether individuals in the general population will become new customers.
In order to develop this project and achieve the objective, it will be carried out in 3 steps:
The pre-processing and dispute of data to know the data.
Unsupervised learning to perform a segmentation
Supervised learning to predict whether individuals in the general population are likely to become clients for Arvato Financial Services

## 🔌Installation
Developed with Python 3 with libraries of:
  * numpy 
  * pandas 
  * matplotlib
  * seaborn
  * sklearn

## 📁File Descriptions
The project worked with 4 dataset:
* Udacity_AZDIAS_052018.csv: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
* Udacity_CUSTOMERS_052018.csv: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
* Udacity_MAILOUT_052018_TRAIN.csv: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
* Udacity_MAILOUT_052018_TEST.csv: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

There are also two Excel spreadsheets that provide more information about the columns represented in the data files:
* DIAS Information Levels — Attributes 2017.xlsx is a top-level list of attributes and descriptions, organized by the informational category.
* DIAS Attributes — Values 2017.xlsx is a detailed mapping of data values for each feature in alphabetical order.

## 📰Blog
The results to the questions are published in this [blog](https://medium.com/@scherrera/getting-to-know-new-customers-through-data-science-e5f961e40307)


## 📚Licensing, Authors, Acknowledgements
This application was made as part of the [Udacity Data Scientist Nanodegree](https://learn.udacity.com/my-programs?tab=Currently%2520Learning) program, who provided the data. The original data was provided by Bertelsmann Arvato Analytics-Udacity.
