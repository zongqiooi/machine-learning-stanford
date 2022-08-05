# Linear Regression
Linear Regression is a supervised Machine Learning model in which the model finds the best fit linear line between the independent and dependent variable. This solution was created by using Octave for the Week 2 Linear Regression assignment for Machine Learning by Andrew Ng, Stanford University. 

# Topics Covered 
- Univariate Linear Regression
  Linear Regression that involves a single variable 
- Multivariate Linear Regression
  Linear Regression that involves multiple variables 
- Cost Function: To determine how well the linear regression model performs for the whole training data  
- Gradient Descent: To minimize the cost function 
- Normal Equation: To minimize cost function by finding the minimum theta 
- Feature Scaling: For gradient descent to maximize its efficiency (only for gradient descent, not for normal equation)  
- Vectorization: To allow the program runs much faster and efficiently 

# Information about Linear Regression 
In this part of this exercise, you will implement linear regression with one variable to predict profits for a food truck. Suppose you are the CEO of a restaurant franchise and are considering different cities for opening a new outlet. The chain already has trucks in various cities and you have data for profits and populations from the cities.

You would like to use this data to help you select which city to expand to next. The file ex1data1.txt contains the dataset for our linear regression problem. The first column is the population of a city and the second column is the profit of a food truck in that city. A negative value for profit indicates a loss.

The final values for θ will also be used to make predictions on profits in areas of 35,000 and 70,000 people.

# Result of Linear Regression
**Cost Function**
 
![image](https://user-images.githubusercontent.com/95561298/183005257-cc44c8c3-adac-4e72-a609-d842d04c4390.png)

**Theta Values Found by Gradient Descent**

![image](https://user-images.githubusercontent.com/95561298/183005485-015bdbdf-fadc-494a-bddb-344dc3d41fbc.png)

**Plot of Linear Regression Line with Training Data**

![image](https://user-images.githubusercontent.com/95561298/183005140-ac413fe8-994d-4e0d-a621-98293a4d3671.png)

**Plot of Cost Function, J(theta_0, theta_1)**

![image](https://user-images.githubusercontent.com/95561298/183005176-ec3f1d6f-941b-4aab-b765-d8668d6593c9.png)

**Plot of Contour for Cost Function, J(theta_0, theta_1)**

![image](https://user-images.githubusercontent.com/95561298/183005186-7e140995-a29b-4fdf-b206-078719a4accb.png)

**Final Prediction Results for Profits in Areas of 35,000 and 70,000 People by Using Linear Regression Model**

![image](https://user-images.githubusercontent.com/95561298/183005547-defa94c1-6500-4f9e-8764-becc1d19427e.png)
