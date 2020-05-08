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

