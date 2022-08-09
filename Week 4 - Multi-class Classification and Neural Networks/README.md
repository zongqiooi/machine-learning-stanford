# Multi-class Classification and Neural Networks
Multi-class Classification is logistic regression that involves multiple classes. Neural Networks is an algorithm that tries to mimic the brain and it is mainly used for complex and non-linear hypotheses. Neural networks are also known as artificial neural networks (ANNs). This solution was created by using Octave for the Week 4 Multi-class Classification and Neural Networks assignment for Machine Learning by Andrew Ng, Stanford University. 

# Topics Covered 
- Multi-class Classification (Logistic Regression that involves more than two classes)
- Neural Networks (An algorithm that tries to mimic the brain)
- Input Layer (Layer of nodes that represent the inputs)
- Hidden Layer (Layer of nodes between the input layer and output layer) 
- Output Layer (Layer of nodes that represent the output)
- Forward Propagation (Input data is fed in the forward direction through the neural networks)

# Information about Multi-class Classification and Neural Networks
## Part 1: Multi-class Classification 
For this exercise, you will use logistic regression and neural networks to recognize handwritten digits (from 0 to 9). Automated handwritten digit recognition is widely used today - from recognizing zip codes (postal codes) on mail envelopes to recognizing amounts written on bank checks. This exercise will show you how the methods you’ve learned can be used for this classification task.

In the first part of the exercise, you will extend your previous implementation of logistic regression and apply it to one-vs-all classification.

## Part 2: Neural Networks
In the previous part of this exercise, you implemented multi-class logistic regression to recognize handwritten digits. However, logistic regression cannot form more complex hypotheses as it is only a linear classifier.

In this part of the exercise, you will implement a neural network to recognize handwritten digits using the same training set as before. The neural network will be able to represent complex models that form non-linear hypotheses. For this week, you will be using parameters from a neural network that we have already trained. Your goal is to implement the feedforward propagation algorithm to use our weights for prediction.

The neural network model is as shown below:

![image](https://user-images.githubusercontent.com/95561298/183638986-f3e914a5-d139-4149-be8f-dda368cbd090.png)

# Result of Multi-class Classification and Neural Networks
## Part 1: Multi-class Classification 
**Training Dataset**

![image](https://user-images.githubusercontent.com/95561298/183640605-950708e1-42d7-4738-b87b-c1b25136ba22.png)

**Cost and Gradient Computed by using Gradient Descent**

![image](https://user-images.githubusercontent.com/95561298/183639383-b7d0de9a-2cc4-46eb-944e-7389b6294121.png)

**Training Set Accuracy by Multi-class Classification**

![image](https://user-images.githubusercontent.com/95561298/183639499-5600866e-e586-4d19-8444-1f17e1f4d56a.png)

## Part 2: Neural Networks
**Training Set Accuracy by Neural Networks**

![image](https://user-images.githubusercontent.com/95561298/183639723-82419672-9189-4a99-80f7-bafb919fe4b5.png)

**Some Prediction Results for Handwritten Digits by Neural Networks**

![image](https://user-images.githubusercontent.com/95561298/183639993-a156056b-e82f-4ea0-b1da-013edbb95a8a.png)

![image](https://user-images.githubusercontent.com/95561298/183640083-e99d61fc-2baf-4c0a-8fb1-5b2514615d2d.png)

![image](https://user-images.githubusercontent.com/95561298/183640142-7f5936b1-f550-4d76-8f98-0f715c95235b.png)

# Conclusion 
The accuracy for Multi-class Classification and Neural Networks are 94.78 and 97.52, respectively. Neural network has higher accuracy because it can form more complex and non-linear hypotheses as compared to multi-class classification. 
