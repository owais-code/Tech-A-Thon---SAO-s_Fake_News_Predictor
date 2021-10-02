# Tech-A-Thon---SAO-s_Fake_News_Predictor
Fake News Predictor model developed by Team SAO, **Shashank, Aakash and Owais** for Tech-A-Thon prefinals, ECE Society, BIT Mesra.


# Repository Description:-

1. SAO_Fake_News_Predictor.ipynb => Fake news predictor Jupyter Notebook format
2. train.zip => Dataset Used (Zipped, ideally unzip using 7-zip)** 
3. train.html => Pandas profiled complete DataSet Description**

# Predictor
Model used: Logistic Regression
Training Data Accuracy Score: 98.65 %
Test Data Accuracy: 97.90 %


# DataSet Description
The data is gathered from github repository which is named as train.csv Dataset. The dataset have 5 attributes of  20800 news. The attributes being id, title, author, text and label.
There 5th attribute is label that is the outcome of each data points. This class variable shows the outcome 0 and 1 for fake news which indicates fake or real news.
Distribution - We made a model to predict fake news and the dataset was very much balanced having around 10413 classes labeled as 1 means Real news and 10387 labeled as 1 means FAKE NEWS.

# Model Used
In our code we have used Logistic Learning ML model. Logistic regression is a supervised learning classification algorithm. It is used to estimate the probability of a binary response based on one or more predictors. They can be continuous or discrete. Logistic regression used when we want to classify or distinguish some data items into categories. It classifies the data in binary form means only in 0 and 1 which refer case to classify patient that is positive or negative for diabetes. Main aim of logistic regression is to best fit which is responsible for describing the relationship between target and predictor variable. Logistic regression is a based on Linear regression model. Logistic regression model uses sigmoid function to predict probability of positive and negative class.
Sigmoid function P = 1/1+e – (a+bx).
 Here, P = probability.
     & b = parameter of Model.
 
 
 
# Libraries Used in the model
1.   Numpy
2.   Pandas 
3.   SKlearn 
4.   RE
5.   NLTK
6.   Port Stemmer

                                                 *Team Description*
                                            1. Md. Owais Ashraf 
                                            2. Aakash Bhardwaj
                                            3. Shashank Shekhar
                                                                   






