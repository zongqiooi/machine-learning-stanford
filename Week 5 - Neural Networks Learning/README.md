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
2) Implement forward propagation to get hΘ(x(i)) for any x(i)
3) Implement the cost function
4) Implement backpropagation to compute partial derivatives
5) Use gradient checking to confirm that your backpropagation works. Then disable gradient checking
6) Use gradient descent or a built-in optimization function to minimize the cost function with the weights in theta

# Result of Neural Networks Learning  
**Cost Computed by Forward Propagation**

![image](https://user-images.githubusercontent.com/95561298/184211651-12bca622-55e1-4b48-921b-ac6db94e8d2d.png)

**Cost Function with Regularization**

![image](https://user-images.githubusercontent.com/95561298/184211826-b6c10983-bdd1-40e1-971f-f90dee94c330.png)

**Sigmoid Gradient**

![image](https://user-images.githubusercontent.com/95561298/184211972-4c9d8d51-3696-485c-a759-d73de5349ec2.png)

**Numerical Gradient Checking Compared with Backpropagation**

![image](https://user-images.githubusercontent.com/95561298/184212543-7afb6479-a216-41ce-8b99-1f1864993384.png)

**Numerical Gradient Checking Compared with Backpropagation with Regularization**

![image](https://user-images.githubusercontent.com/95561298/184212778-5ccbdff4-cd17-4bd8-ae1a-c769eccbcb55.png)

**Visualization of the Hidden Units Computed**

![image](https://user-images.githubusercontent.com/95561298/184213313-2624ecfb-d6e1-4a85-ace8-035a5a8cea01.png)

**Training Set Accuracy by Neural Networks**

![image](https://user-images.githubusercontent.com/95561298/184213012-b783fe7a-5931-43c4-bb79-0aa1d3a2005e.png)
