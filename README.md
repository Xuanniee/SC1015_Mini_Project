# AY21/22 SC1015 Mini Project - Employee Attrition

## Team Members
Team of 3 Students from Lab Group BCF2, Team 4.
Team Member Names:
1. Ng Xuan Yi
2. Fong Ye Xuan
3. Arjun Kumar Nair

## About
This repository is our mini project for SC1015 - Introduction to Data Science & Artificial Intelligence, which focuses on IBM HR Analytics Employee Attrition & Performance Dataset.

During the Covid-19 Pandemic, a phenomenon called "The Great Resignation" has quickly garnered attention in the world. This phenomenon has led to numerous employees deciding to leave their jobs for various reasons. Consequently, our team was left wondering about the reasons behind why people are willing to suddenly quit their jobs, especially during an unstable period like the Covid-19 Pandemic. Hence, we used the IBM Employee Attrition Dataset from Kaggle in hopes of being able to determine the significant factors that are responsible for employee attrition. Thereafter, we hope to use the dataset to see if we could predict employee attrition in advance.

For a detailed walkthrough, please view our jupyter notebook from top to bottom, that is:

---
1. Problem Statement  
2. Dataset Cleaning & Preparation  
  2.1 Removing Unnecessary Data Values  
  2.2 Encoding of Binary Variables  
  2.3 Label Encoding of Categorical Variables  
  2.4 Segmenting our Dataset into Numeric and Categorical Variables  
3. Statistical Analysis [Bivariate & Multivariate]  
4. Basic Exploratory Data Analysis  
  4.1 Box Plots, Histograms, and Violin Plots for Numeric Variables  
  4.2 Visualisation of Dataset [Determine which ML Model to use]  
5. Removal of Outliers [Post-EDA]  
6. Machine Learning  
  6.1 Logistics Regression Model  
  6.2 Decision Tree    
      &emsp;6.2.1 Initial Trial of Decision Tree Classification    
      &emsp;6.2.2 Final trial of Decision Tree Classification (with resampling of data)    
  6.3 Multilayer Perceptron Neural Network  
7. Conclusion  
---

## Contributors
1. @Xuanniee - Multilayer Perceptron Neural Networks and Dataset Cleaning
2. @kenfyxx - Logistics Regression and Basic Exploratory Data Analysis
3. @arjun2000-create - Decision Trees and Removal of Outliers

## Content
Within the repository, there are 3 files that are uploaded.
* SC1015 Project Slides contains the slides that were actually used in our video presentation.
* notebook_SC1015.ipynb is the actual notebook that contains all of our codes.
* train.csv is our dataset that was downloaded from Kaggle and renamed as train. It is not our Training Dataset.

## Problem Definition
* Which combination of factors are the most significant causes for Employee Attrition?
* How can Employee Attrition be predicted?

## Algorithm / Libraries Used
* Pandas
* Seaborn
* Numpy
* Matplotlib
* SckitLearn

## Models Used
* Logistics Regression
* Decision Trees
* Multilayer Percerptron Neural Networks

## Conclusion
* The 8 most important factors in determining Employee attrition from the Dataset are:
  * Overtime [Whether Employees have to work Overtime]  
  * Number of Years since last promotion  
  * Satisfaction with the Working Environment  
  * Number of Companies they worked before  
  * Job Involvement  
  * Monthly Income  
  * Department  
* Variables that are affected by the employees who stay in the company for many years [like Years since Last Promotion] have huge number of outliers. Such outliers have the potential of causing inaccurate analysis and hence have to be removed.
* It is possible to predict whether employees will continue working at their current employment. However, the converse is impossible due to the numerous and wide ranging number of factors that can be broadly categorised into 3 areas:
  * Monetary
  * Familial
  * Societal
* Firms should build and foster their workplaces in such a manner that minimises Employee Attrition as it is impossible to eliminate them.

## Learning Outcomes
* Handling of imbalanced data via Resampling of Data
* Encoding of both Binary and Categorical Variables
* Logistics Regression from SckitLearn
* Multilayered Perceptron Neural Network from SckitLearn
* Github Collaboration

## References
* https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset
* https://towardsdatascience.com/multilayer-perceptron-explained-with-a-real-life-example-and-python-code-sentiment-analysis-cb408ee93141
* https://medium.com/@curryrowan/simplified-logistic-regression-classification-with-categorical-variables-in-python-1ce50c4b137
* https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html
* https://www.linkedin.com/posts/stevenouri_innovation-artificialintelligence-datascience-activity-6913748932347002881-FYAj/?utm_source=linkedin_share&utm_medium=ios_app
* https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html
* https://www.kaggle.com/datasets/itssuru/hr-employee-attrition
