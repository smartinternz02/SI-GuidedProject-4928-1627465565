# SI-GuidedProject-4928-1627465565

TITLE : DETECTION OF OHISING WEBSITES

INTRODUCTION

  Phishing is the most commonly used social engineering and cyber attack.
  Through such attacks, the phisher targets naïve online users by tricking them into revealing confidential information, with the purpose of using it fraudulently. 
  In order to avoid getting phished,
      users should have awareness of phishing websites. 
      have a blacklist of phishing websites which requires the knowledge of website being detected  as phishing.
      detect them in their early appearance, using machine learning and deep neural network  algorithms. 
  Of the above three, the machine learning based method is proven to be most effective than the other methods.
  Even then, online users are still being trapped into revealing sensitive information in  phishing websites.
 
OBJECTIVE

  A phishing website is a common social engineering method that mimics  trustful uniform resource locators (URLs) and webpages. 
  The objective of this  project is to train machine learning models  on the dataset  created to predict phishing websites. 
  Both phishing and benign URLs of websites  are gathered to form a dataset and from them required URL and website content-based features are extracted. 
  The performance level of each model is  measures and compared.
  
APPROACH

Below mentioned are the steps involved in the completion of this project:

Collect dataset containing phishing and legitimate websites from the open source platforms.
Write a code to extract the required features from the URL database.
Analyze and preprocess the dataset by using EDA  techniques.
Divide the dataset into training and testing sets.
Run  selected machine algorithms like SVM, Random Forest, KNN, Logistic regression on the dataset.
Write a code for displaying the evaluation result considering accuracy metrics.
Compare the obtained results for trained models and specify which is better

DATA  SET  DESCRIPTION

From the given dataset there are total
          11055 rows and 31 columns
we dropped index column which don’t have significance
Removed outliners using Zscore In which we have left with
          10035 rows and 31 columns 
Result is taken as Y value as the input URL is classified as  phishing (1) or legitimate (0)
There are no null values in the dataset

MACHINE  LEARNING  MODELS

This is supervised machine learning task. There are two major types of supervised machine learning problems, called classification and regression.
This data set comes under classification problem, as the input URL is classified as  phishing (1) or legitimate (0). 
The machine learning models (classification) considered  to train the dataset in this notebook are:
Decision Tree
Random Forest
KNN
Naïve Bayes
Logistics regression
Support Vector Machines

MODEL EVALUATION 

K-NEARST NEIGHBORS is the best fit model for the given dataset with 96.3 test accuracy






   
