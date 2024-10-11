
# Business Analysis for Investment in House Sales

## Table of Contents
Project Description

Tools

Usage

Project Structure

Data analysis and Results

Contact


## Project Description
### Introduction
Real Estates are one of the biggest investment sectors in USA. In this project, the sales of houses in the year 2014 and 2015 was examined. In investor who wants to invest in reat estate inquired about a feasibility study. Here, the stability of the business over the two years was examined from the market price and market activity perspective. 

### Objectives
* To identify features that impact the prices of house positively and negatively
* To determine if the prices of houses altered over the two years.
* To determine if the market activity is stable over the years.
* To optimize a model that predicts the price of houses with high accuracy.

### Significance
An investor who wants to join the business makes the right decision whether the time is appropriate or not based on the analysis. 

## Tools
Google colab, pandas, numpy, sklearn.pipeline for auromating the process,sklearn.linear_model, sklearn.preprocessing, seaborn

## Usage
The codes in the googlecolab file are active and can be rerun on googlecolab or jupytornotebook.

## Project Structure
data:/ the data folder contians the row data used in this analysis.
src:/ this folder contains the googlecolab file containing the codes.
README:/ this file contains the brief description and guidline for the project content.

## Data Analysis and Result
### Analysis
* The dataframe was imported from the source site url.
* The dataframe cleaned for nulls and unwanted columns removed.
* Data wrangling was done to handle outliers of price.
* The prices of the houses was compared aginst categorical features such as floors, view and wanterfront.
* The number of houses sold per year was calculated 
* models were developed to predict prices by using different number of features.
* Models were refined by using different models and hyperparameters.

### Result
* The total number of houses sold was reduced by half in 2015 when compared to 2014.
* The prices of houses, however, did not show a big change in the two years for all three categorical features (view, waterfront, floors). However, houses with floor number of 3.5 showed a considerable redcution in average price.
* The linear regression model by using features that show higher correlation with price yielded a good fit which was further imprived by 10% by incorporating polynomialFeature into the data input.

## Recommendation
Considering a slow down in the housing marketing activity from 2014 to 2015, it is not advisable to invest right now. However, more data from additional years is required to make a solid analysis.


## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

