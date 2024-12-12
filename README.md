# Term Project - Optimizing Plant Growth
## John Jarvis
## Old Dominion University
## CS 422 - Intro to Machine Learning
## 
## 


## Description/Intro
The intention of this project/experiment is to identify input variables that have a significant effect on the success/failure of plants and use determine an appropriate machine learning model to be able to predict a success/failure outcome based on those input variables. 

The data utilized for the initial setup and analysis of this project can be found at: [(https://github.com/user-attachments/assets/81931456-1267-4bbc-8b9f-a436d8f84516)](https://www.kaggle.com/datasets/gorororororo23/plant-growth-data-classification/code
) and is also available in this repository as a .csv file.


## Running the Program

This program is structured as a Jupyter Notebook (.ipynb). As such there are multiple, many in fact, cells throughout this program. In order for the program to function correctly it should be supplied a .csv file with identical labels and variables; the individual cells in this program must also be executed sequentially for proper function.

This program is designed to display (within the program) important features/metrics that play a role in plant success/failure, as well as provide statistics on variables and models tested.

Finally, below you will find a Table of Contents with brief descriptions highlighting areas of interest and significant points in the process. Throughout the program, you will find "Notes" at the bottom of each section listed below that list several "takeaways" from that particular section.


## Table of Contents

* Setup and Initial Data View

  In this section the user may wish to modify the input file (.csv) if they are utilizing a different dataset (reminder: the structure of the .csv must   have the same labels).
  This section also checks for missing/duplicate values, informs the user of the data types, and provides a basic visualization of the data.


* Visualizing the Data

  This section provides a visualization of each individual variable's distribution in association with the sample set. If using the .csv provided, the initial dataset should be relatively evenly distributed for each categorical and quantitative variable.


* Comparing Individual Variables and Success/Failure

  This section compares individual input variables with their corresponding success/failure results (the target variable). It also displays interaction plots amongst variables.

* Moving Towards a Learning Algorithm

  This section is relatively brief. Here the target variable is established (Growth_Milestone) and label encoding is used for categorical features.

* Statistical Analysis

  In this section we utilize ANOVA and Chi square methods to get an idea for any statistically significant variables.

* Preprocess the Data

  In this section, categorical variables are encoded using one-hot encoding so that they can be utilized in the machine learning tools we'll be assessing.

* Normalize and Standardize the Data

A few transformations that were deemed appropiate/acceptable (if not necessary) are performed on the quantitative data.
  
IMPORTANT!!! 
Note: the transformations used in the initial implementation of this project may not necessarily be appropriate for future/different datasets. The transformations utilized for final information should be assessed according to individual datasets.

* Applying Transformations

  This section merely enacts the choices made in the previous section

* Models

  The bulk of the desired (or undesired) results appear in this section.
  In this section we do several important things:
  * test different models (Random Forest, Logistic Regression, Naive Bayes, Decision Tree, Support Vector, Gradient Boosting, KNN)
  * plot accuracies and highlight the top three
  * perform cross-validation on the top three
  * compare top three models before and after cross-validation

* Summary
  
  Some potential takeaways (from the original dataset's results) are highlighted/discussed. 

