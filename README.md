INTRODUCTION:

An web application on predicting whether it will rain tomorrow or not by using the Rainfall in Australia dataset. This project is tested over lot of ml models like catboost, xgboost, random forest, support vector classifier, knn, naive base, logistic regression. Out of these models catboost performed very well giving an AUC score around and ROC score of 89 far better than others.

TOOLS & TECHNOLOGIES :

* Front-End: HTML, CSS, Bootstrap

* Back-End: Flask

* IDE: Jupyter notebook / Pycharm/ Visual Studio Code

HOW TO RUN THIS APP ?

* First create a virtual environment by using this command:
* conda create -n myenv python=3.6

* Activate the environment using the below command:
* conda activate myenv

* Then install all the packages by using the following command
* pip install -r requirements.txt

* Now for the final step. Run the app
* python app.py

WORK FLOW

# Data Collection: 

Rainfall Prediction in Australia dataset from Kaggle

# Data Preprocessing: 

* Missing Values Handled by Random Sample imputation to maintain the variance

* Categorical Values like location, wind direction are handled by using Target guided encoding

* Outliers are handled using IQR and boxplot

* Feature Selection and was done but didnt perform well it can be seen in testing_notebook / Prediction.ipynb

* Feature Scaling didn’t give a lot of difference it also can be seen in testing_notebook / RainPrediction1.ipynb

* Imbalanced Dataset was handled using SMOTE

# Model Creation:

* Different types of models were tried like catboost, random forest, logistic regression, xgboost, support vector machines, knn, naive bayes.

* Out of these catboost, random forest and support vector machines were top 3

* The conclusion were made using classification metrics. ROC curve and AUC score

OUTPUT:

![image](https://user-images.githubusercontent.com/117114012/214918791-8162eb0e-c4ad-4438-ae93-678ede50bfe8.png)

![image](https://user-images.githubusercontent.com/117114012/214918841-cd7e1f97-5430-46a3-809e-803d11cc1a40.png)

![image](https://user-images.githubusercontent.com/117114012/214918876-a0cb99d4-40a5-40cf-916b-3aa91e679d02.png)

![image](https://user-images.githubusercontent.com/117114012/214918954-bbebaa88-ca80-4960-ab69-b1b09b27fea9.png)

![image](https://user-images.githubusercontent.com/117114012/214919001-677c4251-0741-4639-af6e-a7a5bd262361.png)

![image](https://user-images.githubusercontent.com/117114012/214919037-fc693c70-ce5c-4ee8-b4ef-163476c1127f.png)

                                                  THANKYOU








