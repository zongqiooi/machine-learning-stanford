# Regularized Linear Regression and Bias v.s Variance
Bias and variance are used to indicate whether the data is underfitting or overfitting. Learning curve is used to plot the training error and cross validation error to determine whether is there high bias or high variance in the classifier. This solution was created by using Octave for the Week 6 - Regularized Linear Regression and Bias v.s Variance assignment for Machine Learning by Andrew Ng, Stanford University. 

# Topics Covered 
- Learning Curve (Plot of training error & cross validation error as a function of training set size; used to determine high bias and high variance)
- Bias (To indicate the amount that a model’s prediction differs from the target value, compared to the training data; high bias indicates underfitting) 
- Variance (To indicate how much the estimate of the target function will alter if different training data were used; high variance indicates overfitting)
- Training Set (60% of data that the model will learn)
- Cross Validation Set (20% of data used to determine the regularization parameter)
- Test Set (20% of data used to evaluate performance of the model, also known as the "unseen" examples)
- Precision (To quantify the number of positive class predictions that actually belong to the positive class)
- Recall (To quantify the number of positive class predictions made out of all positive examples in the dataset)
- F1 Score (To compute a score that balances both the concerns of precision and recall in one number)

# Information about Regularized Linear Regression and Bias v.s Variance
## Part 1: Regularized Linear Regression 
In the first half of the exercise, you will implement regularized linear regression to predict the amount of water flowing out of a dam using the change of water level in a reservoir.

## Part 2: Bias v.s Variance 
In this part, you will go through some diagnostics of debugging learning algorithms and examine the effects of bias v.s. variance.

# Result of Regularized Linear Regression and Bias v.s Variance
## Part 1: Regularized Linear Regression 
**Plot of training data** 

![image](https://user-images.githubusercontent.com/95561298/184635232-f18f1f75-0efb-4757-992e-5a11ad9ca185.png)

**Cost Function with Regularization**

![image](https://user-images.githubusercontent.com/95561298/184635429-88caab3c-7b17-473e-8a26-bc5ebb7dc09f.png)

**Gradient with Regularization** 

![image](https://user-images.githubusercontent.com/95561298/184635670-2fc71ea1-a747-480e-97ef-6a25a2a928a0.png)

## Part 2: Bias v.s Variance 

**Regularized Linear Regression with Underfitting** 

![image](https://user-images.githubusercontent.com/95561298/184635740-b69f8f8d-3e31-4245-9458-0300c3b912ad.png)

**Learning Curve with Underfitting (High Bias -> High Training Error and High Cross Validation Error)**

![image](https://user-images.githubusercontent.com/95561298/184635892-20995e7c-bee4-45de-8d11-d73856834f3e.png)

**Cost, Training Error, and Cross Validation Error Computed for Underfitting** 

![image](https://user-images.githubusercontent.com/95561298/184636118-ecf1085c-ab6f-4197-9b97-6661059d62e4.png)

**Regularized Linear Regression with Overfitting** 

![image](https://user-images.githubusercontent.com/95561298/184636342-b14d6628-338f-461e-8f28-cf60bed8bb12.png)

**Learning Curve with Overfitting (High Variance -> Big Gap Between Training Error and Cross Validation Error)**

![image](https://user-images.githubusercontent.com/95561298/184636360-309745db-54f5-48a1-a8bc-73ab1fdb98ac.png)

**Cost, Training Error, and Cross Validation Error Computed for Overfitting** 

![image](https://user-images.githubusercontent.com/95561298/184636412-c9e20fec-54b6-4161-bcd3-a970b7143d50.png)



**Plot of Training Error and Cross Validation Error against λ to Select λ Value**

![image](https://user-images.githubusercontent.com/95561298/184636525-104b850c-eea5-4fee-bdf0-1c4297e9aceb.png)
