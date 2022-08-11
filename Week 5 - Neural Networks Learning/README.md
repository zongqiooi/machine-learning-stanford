# Neural Networks Learning
Backpropagation is an algorithm used to minimize the cost function and to learn the parameters for neural networks. This solution was created by using Octave for the Week 5 Neural Networks Learning assignment for Machine Learning by Andrew Ng, Stanford University. 

# Topics Covered 
- Backpropagation (An alogorithm to minimize the cost function and to learn the parameters for neural networks) 
- Gradient Checking (To compare with the results obtained from backpropagation to ensure no bugs in implementation) 
- Random Initialization (To randomly initialize the theta values in backpropagation so that symmetry ways can be avoided)

# Information about Neural Networks Learning 
In this exercise, you will implement the backpropagation algorithm to learn the parameters for the neural network.

In order to train neural networks, there are a total of 6 steps that are required: 
1) Randomly initialize the weights
2) Implement forward propagation to get h_\Theta(x^{(i)})hΘ(x(i)) for any x^{(i)}x(i)
3) Implement the cost function
4) Implement backpropagation to compute partial derivatives
5) Use gradient checking to confirm that your backpropagation works. Then disable gradient checking.
6) Use gradient descent or a built-in optimization function to minimize the cost function with the weights in theta.


# Result of Neural Networks Learning  
**



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
