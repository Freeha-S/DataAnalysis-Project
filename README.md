## DataAnalysis-Project

# Fundamentals of Data Analysis- Assessment 2019

## Module: Fundamentals of Data Analysis

## Lecturer: Dr Ian McLoughlin

## Table of Contents <a name="Table"></a>
1. [Introduction](#introduction)
   - [Objective](#objective)
   - [Project Plan](#project_plan)
   - [Technologies Used](#technology)
2. [Background Information](#background)
3. [Statistical Analysis](#statistics)
4. [Regression](#regression)
5. [Conclusion](#conclusion)
6. [References](#Reference)

# Introduction <a name="introduction"></a>
This repository contains all files and folders of my submissions for Fundamentals of Data Analysis- Assessment 2019.

This assessment is for Module "Fundamentals of Data Analysis" at GMIT.This repository contains
 
 1. Readme.md
 2. DA-Assessment2019.ipynb
  
To download this repository 
1. from https://github.com/Freeha-S/DataAnalysis-Project 
2. click on [Clone and download]
3. select Download zip
4. save it in a local folder on your machine.
5. open the command line and go to the folder containing repository using cd command
6. type jupyter notebook it will open in browser  show you contents of folder
7. click open the file DA-Assessment2019.ipynb

To view online in nbviewr
1. click the link https://nbviewer.jupyter.org/
2. copy the link : https://github.com/Freeha-S/DataAnalysis-Project/blob/master/DA-Assessment2019.ipynb in given textbox
3. click Go!button or press return key

## Objective<a name="objective"></a>
The aim of this project is to research the tips dataset. That include following tasks

1. Create a jupyter notebook that use descriptive statistics and plots to describe the tips dataset.
2. Discuss and analyse whether there is a relationship between the totalbill and tip amount
3. Analyse the relationship between the variables within the dataset.


## Project Plan <a name="plan"></a>
- **Research**<br>
   Use online resources to research the Dataset 
- **Create a Github Repository**<br>
   Create a github repository and start editing readme.md
- **Make a List of the Project Requirements**<br>
   Make a list of objective
- **Time Management**<br>
   As I need some extra time for writing the description and analysis so i need to complete the code first and than add descriptions. It took so long in my previous project and documentation is not my strong point.

## Technologies Used <a name="technology"></a>
- Jupyter notebook
- python 3.7.1
- Github
- pandas ,seaborn,numpy,scikit-learn and matplotlib libraries

# Background Information <a name="background"></a>
<p align="center"><img src="images/tips.jpg"> </p>
*source: https://www.tripsavvy.com/how-to-calculate-a-restaurant-tip-1329250*

**tips dataset**

Source of dataset: 

Bryant, P. G. and Smith, M. A. (1995), Practical Data Analysis: Case Studies in Business Statistics, Richard D. Irwin Publishing, Homewood, IL.

In one restaurant, a food server recorded this data on all customers they served during an interval of two and a half months in early 1990. The restaurant, located in a suburban shopping mall, was part of a national chain and served a varied menu. In observance of local law, the restaurant offered to seat in a non-smoking section to patrons who requested it. Each record includes a day and time. sex column contain the sex of person paying for the meal source:https://www.kaggle.com/ranjeetjain3/seaborn-tips-dataset

This dataset contain 244 rows and 7 columns of data, columns are the variables and rows are the number of observations.

__Columns__
 - **total_bill:** The amount of total bill
 - **tip :** the amount of tip 
 - **sex :** gender (Male,Female)
 - **smoker:** value(Yes, No)
 - **day :** days of week(Thur, Fri, Sat, Sun)
 - **time :** time(Lunch, Dinner)
 - **size :** number of people in group (1,2,3,4,5,6)
 
| Categorical data column|
| ------------- |
| - sex         |
| - smoker|
| - day|
| - time |

| Numerical data column|
|------------- |
| - total_bill |
| - tip        |
| - size |
 

# Statistical Analysis <a name="statistics"></a>
Statistical Analysis is a process of understanding how variables in a dataset relate to each other and how those relationships depend on other variables. There are several types of statistical analysis.

The type of statistical analysis used for tips dataset in this notebook are.

**Expolatory Data Analysis-** EDA is an analysis approach that focuses on identifying general patterns in the data and to find previously unknown relationships.

**Descriptive statistic** is used to describe! It describes the basic features of information and shows or summarizes data in a rational way. Descriptive statistics is a study of quantitatively describing.

**Predictive analytics** uses statistical algorithms and machine learning techniques to define the likelihood of future results, behavior, and trends based on both new and historical data.

# Regression <a name="regression"></a>
In statistical modeling, regression analysis is a set of statistical processes for estimating the relationships between a dependent variable and one or more independent variables. The most common form of regression analysis is linear regression.

The process of fitting a line to a set of data is called linear regression and the line of best fit is called regression line. The regression line provides a model of a linear association between two variables.

A linear regression line has an equation of the form Y = a + bX, where X is the explanatory variable and Y is the dependent variable. The slope of the line is b, and a is the intercept (the value of y when x = 0). In tips dataset we are looking at the tip and total_bill relationship, total_bill as an independent variable and tip as dependent varable.

# Conclusion <a name="conclusion"></a>
after analyising this data set it was clear that there is a linear relationship between total_bill and tip.And how scikit-learn package made it so easy to fit a linear regression model.


# References <a name="References"></a>
1. Robin H. Lock, Patti Frazer Lock, Kari Lock Morgan, Eric F. Lock, Dennis F. Lock, 2016, Statistics: Unlocking the Power of Data
2nd Edition, Wiley
2. The Key Types of Statistical Analysis available at http://intellspot.com/types-statistical-analysis/ accessed on 25/11/2019