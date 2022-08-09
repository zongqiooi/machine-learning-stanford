# Multi-class Classification and Neural Networks
Multi-class Classification is logistic regression that involves multiple classes. Neural Netoworks is an algorithm that try to mimic the brain and it is mainly used for complex and non-linear hypothesis. This solution was created by using Octave for the Week 4 Multi-class Classification and Neural Networks assignment for Machine Learning by Andrew Ng, Stanford University. 

# Topics Covered 
- Binary Classification (Logistic Regression that involves two classes only) 
- Multi-class Classification (Logistic Regression that involves more than two classes)
- Sigmoid Function / Logistic Function (Function that allows the output of logistic regression to be within 0 to 1)
- Underfitting (Logistic regression model too simple, results in inaccurate prediction because of the wrong hypothesis)
- Overfitting (Logistic regression model too complex, results in inaccurate prediction because it fails to generalize on new examples)
- Regularization (To solve the overfitting problem by adding a new regularization term at the end of the equation) 
- Decision Boundary (Line that separates the data into two sets for logistic regression)

# Information about Logistic Regression 
## Part 1
In this part of the exercise, you will build a logistic regression model to predict whether a student gets admitted into a university.

Suppose that you are the administrator of a university department and you want to determine each applicant’s chance of admission based on their results on two exams. You have historical data from previous applicants that you can use as a training set for logistic regression. For each training example, you have the applicant’s scores on two exams and the admissions decision.

After learning the parameters, the model will be used to predict whether a particular student with an Exam 1 score of 45 and an Exam 2 score of 85 will be admitted. 

## Part 2
In this part of the exercise, you will implement regularized logistic regression to predict whether microchips from a fabrication plant passes quality assurance (QA). During QA, each microchip goes through various tests to ensure it is functioning correctly.

Suppose you are the product manager of the factory and you have the test results for some microchips on two different tests. From these two tests, you would like to determine whether the microchips should be accepted or rejected. To help you make the decision, you have a dataset of test results on past microchips, from which you can build a logistic regression model.

Then, the accuracy of logistic regression will be determined. 

# Result of Logistic Regression
## Part 1
**Cost and Gradient Computed by using Gradient Descent**

![image](https://user-images.githubusercontent.com/95561298/183305688-d23d75b0-2a6a-43e2-93cc-8029f8ddbc61.png)
 
**Cost and Gradient Computed by using fminunc() Optimization Algorithm**

![image](https://user-images.githubusercontent.com/95561298/183305772-9234e860-ecf0-4125-8bb2-0570ff8c178e.png)

**Final Prediction Results for the Admission Probability of a student with an Exam 1 score of 45 and an Exam 2 score of 85 by Using Logistic Regression Model**

![image](https://user-images.githubusercontent.com/95561298/183305785-53861abc-4823-4791-9b4e-387995acadeb.png)

**Accuracy of Logistic Regression Model**

![image](https://user-images.githubusercontent.com/95561298/183305856-c55a64f2-633f-46c4-aa8d-1f829b50b7bc.png)

**Plot of Decision Boundary for Logistic Regression with Training Data**

![image](https://user-images.githubusercontent.com/95561298/183305863-b8aece2f-aa29-431f-8a4c-eba3c0eac737.png)

## Part 2
**Cost and Gradient Computed by using Gradient Descent**

![image](https://user-images.githubusercontent.com/95561298/183305924-12901c77-4f2c-4c42-99b4-2a7138ec28d3.png)
 
**Cost and Gradient Computed by using fminunc() Optimization Algorithm**

![image](https://user-images.githubusercontent.com/95561298/183305952-68b95b80-5879-44e5-80da-e5d0c43abb80.png)

**Accuracy of Logistic Regression Model**

![image](https://user-images.githubusercontent.com/95561298/183305899-2332304d-24cb-48d5-9d97-28fea194c7d1.png)

**Plot of Decision Boundary for Logistic Regression with Training Data**

![image](https://user-images.githubusercontent.com/95561298/183305885-a4d92545-3058-4fcd-b640-5fd21dde5ef8.png)
