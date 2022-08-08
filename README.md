## Insurance-Premium-Prediction 
Application url:
[Insurance Premium Prediction](https://premium-pred-app.herokuapp.com/)

### Problem Statement : 
The goal of this project is to give people an estimate of how much they need based on
their individual health situation. After that, customers can work with any health
insurance carrier and its plans and perks while keeping the projected cost from our
study in mind. This can assist a person in concentrating on the health side of an
insurance policy rather than the ineffective part.

### Dataset : 
Dataset Link : [link](https://www.kaggle.com/datasets/noordeen/insurance-premium-prediction)


### Approach
We needed to predict the amount of expenses billed by the heathcare for insurance which could assit a person 
in concentrating on the health side of aninsurance policy rather than the ineffective part.

Applying machine learing tasks like Data Exploration, Data Cleaning, Feature Engineering, Model Building and model testing to build a solution that should able to predict the premium of the person for health insurance. 

#### EDA: Exploratory Data Analysis 
Firstly, data was analysed using pandas,numpy , matplotlib, seaborn to get insights about the data.

Data cleaning and Feature Engineering were performed to make the dataset understandable by the machine.

#### Model Building : 
First the dataset was split into train and test set. Then the model was trained using different ML algorithms like 
1. Linear Regression
2. Random Forest Regressor
3. SVM( Support Vector Machine)
4. Decision Tree

#### Model Evaluation and Model Selection:
The trained model was being evaluated using different parameters. 
Then the accuracy was being tested on test dataset .
The model that performed was being chosen for further predictions.


#### Webbpage and Deployment:
 Created a web application that takes all the necessary inputs from the user & shows the output. Then deployed project on the Heroku Platform.



 ### Project Pipeline
 #### 1. Data Ingestion
 Data ingestion is the process in which unstructured data is extracted from one or multiple sources and then prepared for training machine learning models.

 #### 2. Data Validation:
Data validation is an integral part of ML pipeline. It is checking the quality of source data before training a new model.
It focuses on checking that the statistics of the new data are as expected (e.g. feature distribution, number of categories,data drift  etc).

#### 3.  Data Transformation
Data transformation is the process of converting raw data into a format or structure that would be more suitable for model building.
It is an imperative step in feature engineering that facilitates discovering insights.

#### 4.Model Training
Model training in machine learning is the process in which a machine learning (ML) algorithm is fed with sufficient training data to learn from.

#### 5. Model Evaluation
Model evaluation is the process of using different evaluation metrics to understand a machine learning model’s performance, as well as its strengths and weaknesses.
Model evaluation is important to assess the efficacy of a model during initial research phases, and it also plays a role in model monitoring.


#### 6. Model Deployment
Deployment is the method by which we integrate a machine learning model into production environment to make practical business decisions based on data.