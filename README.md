# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Kaggle Competition - Starter

## Problem Statement

Due to the recent epidemic of West Nile Virus in the Windy City, the Department of Public Health set up a surveillance and control system to help collect data on mosquito numbers, presence of West Nile Virus for captured mosquitos, and weather events.

As part of the Disease And Treatment Agency, division of Societal Cures In Epidemiology and New Creative Engineering (DATA-SCIENCE), we have been tasked to assess the viability of the current spray model, as well as to try and predict occurrence of West Nile Virus in Chicago, to help further refine the current pest management model.

Mosquitoes enjoy wet and warm climates and are most active in temperatures above 80&deg;F. Conversely, when temperatures go below 50&deg;F, mosquitoes go dormant.

The lifecycle for the Culex Pipiens, the most common species of mosquito caught in Chicago, typically range from 2-4 weeks, and even less than a week in the heat of summer.

Our project will seek to:
1. Determine the effectiveness of sprays on the mosquito population
2. Predict the occurence of West Nile Virus
3. Help provide guidelines by which to apply future sprays

## Contents
* Data import, helper functions, cleaning and imputation of missing values
* EDA: Previewing Data and Highlighting Outliers
* Modelling
* Applying our selected model on the Kaggle test set
* Cost-Benefit Analysis and Conclusion

## Executive Summary
TODO: Insert brief writeup on findings


## Dataset

The dataset, along with description, can be found here: [https://www.kaggle.com/c/predict-west-nile-virus/](https://www.kaggle.com/c/predict-west-nile-virus/).


* [`train.csv`](./assets/train.csv): Training set consists of data from 2007, 2009, 2011, and 2013. 
* [`test.csv`](./assets/test.csv): Test set consists of data required to predict results for 2008, 2010, 2012, and 2014.
* [`weather.csv`](./assets/weather.csv): Weather data from 2007 to 2014 of 2 stations
* [`spray.csv`](./assets/spray.csv): GIS data of spraying efforts in 2011 and 2013 

### Data Dictionary
You can access the data dictionary, split into markdown format [*here*](https://github.com/kkhalis/project_4/blob/master/DataDictionary.md).

You can also access the detailed description of weather info in the Data Dictionary [*here*](https://github.com/kkhalis/project_4/blob/master/assets/noaa_weather_qclcd_documentation.pdf)



## Conclusion

TODO: Insert writeup of cost-benefit analysis and conclusion here.


## To remove below once above is completed.


**This is also where you will be submitting your code for evaluation**. The public leaderboard uses roughly 30% of the dataset to score an AUC (Area Under Curve) metric.

> If you do not already have a Kaggle account, you will need to sign up on the website.  Also note that you will be submitting a "Late Submission" on Kaggle because the official competition has ended.  You can use the leaderboard to see how your results compare against roughly 1300 other data science teams!

You can submit predictions as many times as you want to Kaggle, but there is a limit of 5 submissions per day.  Be intentional with your submissions!


#### Navigating Group Work

This project will be executed as a group.  To make your team as effective and efficient as possible you should do the create a shared GitHub repo and project planning document as described in the deliverables section below.

## Deliverables

**GitHub Repo**

1. Create a GitHub repository for the group. Each member should be added as a contributor.
2. Retrieve the dataset and upload it into a directory named `assets`.
3. Generate a .py or .ipynb file that imports the available data.

**Project Planning**

1. Define your deliverable - what is the end result?
2. Break that deliverable up into its components, and then go further down the rabbit hole until you have actionable items. Document these using a project managment tool to track things getting done.  The tool you use is up to you; it could be Trello, a spreadsheet, GitHub issues, etc.
3. Begin deciding priorities for each task. These are subject to change, but it's good to get an initial consensus. Order these priorities however you would like.
4. You planning documentation (or a link to it) should be included in your GitHub repo.

**EDA**

1. Describe the data. What does it represent? What types are present? What does each data points' distribution look like? Discuss these questions, and your own, with your partners. Document your conclusions.
2. What kind of cleaning is needed? Document any potential issues that will need to be resolved.

**Note:** As you know, EDA is the single most important part of data science. This is where you should be spending most of your time. Knowing your data, and understanding the status of its integrity, is what makes or breaks a project.

**Modeling**

1. The goal is of course to build a model and make predictions that the city of Chicago can use when it decides where to spray pesticides! Your team should have a clean Jupyter Notebook that shows your EDA process, your modeling and predictions.
2. Conduct a cost-benefit analysis. This should include annual cost projections for various levels of pesticide coverage (cost) and the effect of these various levels of pesticide coverage (benefit). *(Hint: How would we quantify the benefit of pesticide spraying? To get "maximum benefit," what does that look like and how much does that cost? What if we cover less and therefore get a lower level of benefit?)*
3. Your final submission CSV should be in your GitHub repo.

**Presentation**
* Audience: You are presenting to members of the CDC. Some members of the audience will be biostatisticians and epidemiologists who will understand your models and metrics and will want more information. Others will be decision-makers, focusing almost exclusively on your cost-benefit analysis. Your job is to convince both groups of the best course of action in the same meeting and be able to answer questions that either group may ask.
* The length of your presentation should be about 10 minutes (a rough guideline: 1 minute intro, 5 minutes on model, 2 minutes on cost-benefit analysis, 2 minute recommendations/conclusion).  Touch base with your local instructor... er, manager... for specific logistic requirements!
