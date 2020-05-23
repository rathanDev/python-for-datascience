
Udemy wishlist

https://www.udemy.com/course/python-coding/
Python A-Z™: Python For Data Science With Real Exercises!
$10.99
Programming In Python For Data Analytics And Data Science. Learn Statistical Analysis, Data Mining And Visualization
4.6 (14,518 ratings)
108,563 students enrolled
Created by Kirill Eremenko, SuperDataScience Team
Last updated 5/2020

https://udemy.com/course/microservices-with-node-js-and-react/
Microservices with Node JS and React
Build, deploy, and scale an E-Commerce app using Microservices built with Node, React, Docker and Kubernetes
BESTSELLER
$9.99
4.8 (658 ratings)
8,226 students enrolled
Created by Stephen Grider
Last updated 5/2020
46 hours on demand video

https://www.udemy.com/course/django-3-make-websites-with-python-tutorial-beginner-learn-bootstrap/
Django 3 - Full Stack Websites with Python Web Development
Build 3 stunning websites, learn Back and Front End Web Development, deploy your site with HTML5, CSS3 and Bootstrap 4
HIGHEST RATED
4.7 (664 ratings)
3,183 students enrolled
Created by Nick Walter
Last updated 3/2020
funny guy, interesting
8.5 hours of video




Traversy
may be it can be found on youtube
https://www.udemy.com/course/python-django-dev-to-deployment/

## ----- ----- ## ----- ----- ## ----- ----- ## ----- ----- ## 
Error: Anaconda is already running

C:\Users\user>tasklist | findstr "pythonw"                                                                              
pythonw.exe                   8580 Console                    5     14,984 K                                            
pythonw.exe                  29516 Console                    5    359,844 K  

C:\Users\user>taskkill /pid 29516 /f                                                                                    
SUCCESS: The process with PID 29516 has been terminated. 

## ----- ----- ## ----- ----- ## ----- ----- ## ----- ----- ## 


## ----- ----- ## ----- ----- ## ----- ----- ## ----- ----- ## 

udemy.com 

Machine Learning 

77. Supervised Learning 

Supervised learning algorithms are trained using labelled examples,
such as input where the output is known.

Spam vs Legitimate email 
Positive vs Negative movie review 

                                                                        Test Data ->
DataAcquistion -> DataCleaning -> Model Training & Building --------------------------------> Model Testing -> Model Deployment    
                                                                  <- Adjust model params

Data is often split into 3 sets 

Training Data       -   Train models  
Validation Data     -   Hyperparameters to adjust 
Test Data           -   to get performance metrics 


78. Evaluating performance - Classification Error metrics 

Key Classification metrics 
Accuracy 
Recall 
Precision 
F1-Score 

In real world,
not all incorrect or correct matches hold equal value 

Recall 
ability of a model to find all the relevant cases within a dataset.
no of true positives / (number of true positive + number of false negative)

Precision 
ability to identify only the relevant points 
no of true positives / (no of true positives + number of false positives)

Recall and Precision 
Often there is a trade-off between Recall and Precision 
While 
recall expresses the ability to find all relevant instances in a dataset,
precision expresses the propotion of the datapoints our model says relevant actually were relevant 

F1-Score 
Optimal blend of precision and recall 

True  Positive   - Correct   Prediction  
True  Negative   - Correct   Prediction 
False Positive   - Incorrect Prediction 
False Negative   - Incorrect Prediction 

Often models are used as quick diagnostic tests to have before having a more invasive test 
(getting a urine test before getting a biopsy)      [biopsy-examination of a tissue removed from a living body Eg:BoneMarrowBiopsy]

79. Evaluating Performance - Regression Error Metrics 

80. Machine Learning with Python 

SciKit Learn 

from sklearn.family import Model 
from sklearn.linear_model import LinearRegression 

Choosing an algorithm 
Classification 
Clustering 
Regression 

81. Linear Regression Theory 

82. Model selection updates for SciKit Learn 

83. Linear Regression with Python - Part 1 


If it's not normally distributed,
Linear Regression might not be the correct choice for this data model.


88. Bias Variance Trade off 

point where we add just noise 
by adding model complexity 

The  training error goes down, but the test error goes up 
Bcz the model overfit 

89. Logistic Regression Theory 

Logistic Regression for Classification 

spam vs ham emails 
load default yes/no 
disease diagnosis 

can't use a normal linear regression model on binary groups.
It won't lead to a good fit.

Confusion Matrix 
True positive 
True negative 
False positive 
False negative 

Accuracy = (TP + TN) / total 

90. Logistic Regression with Python - part 1 



95. KNN Theory

K nearest neighbors is a classification algorithm that operates on a very simple principle.
Data on Dogs and Horses with heights and weights.

Pros:
Very simple 
Training is trivial 
Works with any number of classes 
Easy to add more data 
Few parameters 
    K
    Distance metric 

Cons:
High prediction cost (worse for large data sets)
Not good with high dimensional data
Categorical features don't work well

A common interview task for a data scientist:
Classify an anonymized data without knowing the context of it.

 

99. Intro to Tree methods

Asking friend to come and play Tennis with me 

Random Forests 

100. Decision Trees and Random Forests with Python 

104. SVM Theory 

Support Vector machines 

data belongs to one of 2 categories

for non-linearly separable data 
using kernel trick it can be seperated 
by viewing it in multidiemension 


108. Intro to K Means Clustering

Unsupervised learning

Cluster similar documents
cluster customers based on features
market segmentation
identify similar physical projects 

Sum of Squared Error (SSE)

Elbow method 
- Choose the K,
    at which the SSE decreases abruptly

112. Principal Component Analysis

114. Recommender Systems

CF - Collaborative filtering
2 types 
Memory based Collaborative filtering
Model based collaborative filtering

For mathematical savvies 

117. Intro to Natural Language Processing

Bag of words
corpus
Term Frequency - Inverse Document Frequency






















