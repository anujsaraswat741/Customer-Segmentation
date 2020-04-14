# Customer-Segmentation

This is a Capstone project of Udacity: Data Scientist Nanodegree Program

In this project, Supervised and Unsupervised machine learning models were used to analyze the demographic data of customers of a mail-order 
company in Germany. The data was compared against the general population to identity the core customer base of the mail-order company.

Please find the medium article explaining the proposed approach [here](https://medium.com/@anujsaraswat/customer-segmentation-a-better-way-to-detect-and-target-customers-f6a06ce533b3)

***

**Directories**

Data: contains files describing the features.

**Dependencies**
* sklearn==0.22.2
* pandas==1.0.3
* numpy==1.18.1
* seaborn==0.10.0
* matplotlib==3.1.3
* progressbar==2.5

***

Following models were used to analyze the data:

**Unsupervised Models**

To perform customer segmentation and identify clusters/segments from general population are most similar to  mail-order company's customer base.

1. PCA
2. Kmeans

**Supervised Models**

To identify individuals who would respond positively to the targeted campaign and possibly turn into customers of the mail-order company.

1. AdaBoostRegressor
2. GradientBoost Regressor
3. XGBoostRegressor

The model achieves AUC ROC score of 0.79201 on [kaggle](https://www.kaggle.com/c/udacity-arvato-identify-customers/leaderboard)

