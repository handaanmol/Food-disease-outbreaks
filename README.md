# Food-disease-outbreaks
Performing Machine Learning on a Food-based illness dataset available from CDC and FDA to predict illness counts based on State, Month, Location and type of Food Consumed 

<p align="center">
  <img src="https://github.com/handaanmol/Food-disease-outbreaks/blob/master/images/project_logo.png" alt="Stop Foodborne Illness" width="226">
  <br>
  <a href="https://travis-ci.org/lord/slate"><img src="https://travis-ci.org/lord/slate.svg?branch=master" alt="Build Status"></a>
</p>

<p align="center"> <b> A Data Science- Machine Learning Initiative to predict Foodboorne Disease Outbreaks </b></p>

<p align="center"><img src="https://github.com/handaanmol/Food-disease-outbreaks/blob/master/images/IST%20718%20poster.png" width=700 alt="Screenshot of Example Documentation created with Slate"></p>

Features
------------

* **Supervised Learning System** — It takes into consideration the key features like State, Month, Year, Food Consumed, Location of Food Consumption to predict the possible number of illnesses. This is surely helpful for Centre for Disease Control and Prevention to taking neccessary measures ahead of time to mitigate the risks.

* **Type of Predictions Made**   
- 1. Prediction of Illnesses Count based on the features mentioned above
- 2. Classification of Diseases as High Scaled or Low Scaled
- 3. Time Series Analysis to understand the impact of Month and Year on the Oubtreak Impact

* **Algorithms Used** — There are multiple algorithms involved in this system to tackle the outbreaks.
- 1. Regression Models - Linear Regression, Linear Regression with Regularization and Cross Validation, Decision                                                 Tree Regression, Random Forest Regression
- 2. Classfication Model- Logistic Regression
- 3. Time Series Analysis - Base Time Series Model, Rolling Average Model
                        
* **Data Cleansing and Normalization** — 1. Data is messy and hence we have perfomed data cleaning using pandas to ensure that data loss is minimal and the values which we are predicted are uniformly distributed to ensure best outcomes. Example of operations - Removing null values, replacing null values with mean values, removing non impactful features, taking Logarithm of prediction values to bring it on a normalized scale.

* **Data Visualization to represent findings** — At many instances, the data has been represented using Matplotlib, Seaborn and Pandas library to assist stakeholders in understanding the findings in the easist and user friendly way.

* **String Indexing, One Hot Encoding** - String Indexing and One hot encoding is performed

