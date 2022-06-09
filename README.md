# Data Science Portfolio

Repository containing portfolio of Data science machine learning, Natural Language Processing and computer Vision projects completed by me for academic, self learning and hobby purpose. The files above are presented in form of iPython notebooks.


## Instructions for Running Python Notebooks Locally

1. Install dependencies using [requirements txt](/requirements.txt)
2. Run notebooks as usual by using anaconda, colab, Vscode etc.

## Contents

* ## Machine Learning
  - [Property Price Prediction](/ML%20micro%20Projects/USING_OLS_Property%20Price%20Prediction%20Case%20Study.ipynb): A model to predict the value of a given house in a region real estate market using various statistical analysis tools. Identified the best price that a client can sell their house utilizing machine learning.
  - [Vaccine Prediction](/ML%20micro%20Projects/Vaccine%20Usage%20Prediction_using_Logistic_Regg.ipynb): The data set is the response of people to the h1n1 flu vaccine related questionnaire. The respondents are people of age 6 months and older. This survey was designed to monitor the influenza immunization coverage in 2009-10 season. Machine learning techniques may aid a more efficient analysis in the prediction of how likely the people are to opt for the flu vaccine. In this case study, we predict, how likely it is that the people will take a H1N1 flu vaccine.
  - [Vehicle Performance Prediction](/ML%20micro%20Projects/Vehicle_performance_using_SGD.ipynb): The dataset contained information of various vehical mileage and various factors on which mileage was dependent, I tried to keep the best columns which influence the mileage of the vehicle. And built two models one with OLS and the other one with SGD
  - [Taxi Price Prediction Using DTree & Rforest](/ML%20micro%20Projects/Rforest_Taxi%20Fare%20Prediction.ipynb): In this project I tried to predict the taxi fare for a taxi ride in New York City from a given pickup point to the agreed dropoff location. Decision tree and Random Forest regressor is used for the fare prediction. (NOTE: This was a learning project so I didn't used library such as Geopandas so the prices are for shortest distance not the actual route)
  - [Predicting whether the cancer is benign or malignant Using Ensemble](/ML%20micro%20Projects/Ensemble_learning_case_study.ipynb): The objective of the dataset is to predict whether Predict whether the cancer is benign or malignant. Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. Models which are used in this Case Study are Bagging meta_estimator, AdaBoost, XGBM
  - [Predicting Term Deposit Subscription by a client Using SVM](/ML%20micro%20Projects/SVM_Case_Study.ipynb): The objective of the dataset is to predict whether or not a client will subscribe to the term deposit. The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. The dataset consists of several predictor variables and one target variable, Outcome. Predictor variables includes the age, job, marital status, and so on.
  - [Market Positioning Of Mobiles_KNN](/ML%20micro%20Projects/USING_KNN_Market%20Positioning%20Of%20Mobile.ipynb): There is a new mobile company and the CEO wants to give tough fight to big companies like Apple,Samsung etc. He has no idea of how to estimate price of mobiles his company creates. A simple assumption of the prices will not be profitable in this competitive world. To solve this problem he collects sales data of mobile phones of various companies. And here I tried to build a model to help my hippothetical customer.


* ## Time Series
  - [Forecasting the Sales of a Furniture store Using SARIMAX](/ML%20micro%20Projects/TIME_SERIES_Sales_of_Furniture.ipynb): I found this Dataset of Kaggle to practice my Time Series skills. This is model that I built for forecasting the sales of a Furniture store.
 
* ## Clustering
  - [Analyzing tred in E-Commerce Kmeans](/Clustring_project/CLUSTRING_KMEANS.ipynb): A key challenge for e-commerce businesses is to analyze the trend in the market to increase their sales. The trend can be easily observed if the companies can group the customers; based on their activity on the e-commerce site. This grouping can be done by applying different criteria like previous orders, mostly searched brands and so on. The machine learning clustering algorithms can provide an analytical method to cluster customers with similar interests.
  - [Travel Review Clustering by heirarchical](/Clustring_project/HEIRARCHICAL_CLUSTERING_Travel%20Review%20Clustering.ipynb): This data set is populated by capturing user ratings from Google reviews. Reviews on attractions from 24 categories across Europe are considered. Google user rating ranges from 1 to 5 and average user rating per category is calculated.

* ## NLP
  - [Consumer Complaint Classification](/Customer_complain/Copy%20of%20consumer_complaint1.ipynb): Bank receives a lot of complaint in this model I tried to classify the complaints into three main categories. I used RNN artituctre which I built from scratch and then passed the data through that and classified them into various categories before that I cleaned the data through various steps of NLP cleaning, such as removing unwanted symbols followed by STOPWORDS removal, Creating word cloud for better visualization of the words, then came tokenizing the words in the dataset followed by word embedding.
  - [Upcoming NLP Projects](Data_science-Machinelearning-Deeplearning/NLP/): Topic will be updated by 15th June 2022. 



