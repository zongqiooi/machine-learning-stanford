# Anomaly Detection and Recommender
Anomaly detection is used to identify data points in data that don't fit the normal patterns. Recommender is a system that recommends a movie based on the dataset of movie ratings. This solution was created by using Octave for the Week 9 - Anomaly Detection and Recommender for Machine Learning by Andrew Ng, Stanford University. 

# Topics Covered 
- Anomaly Detection (To identify data points in data that don't fit the normal patterns)
- Recommender (To provide new recommendations based on the old dataset)
- Collaborative Filtering (To filter data from user reviews and make personalized recommendations for users with similar preferences) 

# Information about Anomaly Detection and Recommender
## Part 1: Anomaly Detection
In this exercise, you will implement an anomaly detection algorithm to detect anomalous behavior in server computers. The features measure the throughput (mb/s) and latency (ms) of the response of each server. While your servers were operating, you collected m = 307 examples of how they were behaving, and thus have an unlabeled dataset {x(1), . . . , x(m)}. You suspect that the vast majority of these examples are “normal” (non-anomalous) examples of the servers operating normally, but there might also be some examples of servers acting anomalously within this dataset.

You will use a Gaussian model to detect anomalous examples in your dataset. You will first start on a 2D dataset that will allow you to visualize what the algorithm is doing. On that dataset, you will fit a Gaussian distribution and then find values that have very low probability and hence can be considered anomalies. After that, you will apply the anomaly detection algorithm to a larger dataset with many dimensions.

## Part 2: Recommender 
In this part of the exercise, you will implement the collaborative filtering learning algorithm and apply it to a dataset of movie ratings.2 This dataset consists of ratings on a scale of 1 to 5. The dataset has n_u = 943 users, and n_m = 1682 movies.

In the next parts of this exercise, you will implement the function cofiCostFunc.m that computes the collaborative filtering objective function and gradient. After implementing the cost function and gradient, you will use fmincg.m to learn the parameters for collaborative filtering.

# Result of Anomaly Detection and Recommender
## Part 1: Anomaly Detection
**Plot of Dataset**

![image](https://user-images.githubusercontent.com/95561298/185479192-fa190256-d852-4b5a-adef-58a8e253a690.png)

**Plot of Gaussian Distribution Contours of the Distribution Fit to the Dataset**

![image](https://user-images.githubusercontent.com/95561298/185479296-43c215fe-fa34-4b70-bdae-ff31bee71f2e.png)

**Best Epsilon Threshold and F1 Value Computed**

![image](https://user-images.githubusercontent.com/95561298/185479441-71448246-66bd-4b10-a556-8370d9851cee.png)

**Plot of Anomalies Detected**

![image](https://user-images.githubusercontent.com/95561298/185479649-7bf55b0b-b85b-4660-9fbd-ac5941cee91c.png)

**Best Epsilon Threshold, F1 Value, and Number of Outliers Computed**

![image](https://user-images.githubusercontent.com/95561298/185479951-f5678780-83ed-4c7d-bc46-192aa280ef18.png)

## Part 2: Recommender 
** Cost Computed Without Regularization**

![image](https://user-images.githubusercontent.com/95561298/185480342-4aa2af7d-437c-4924-85dc-8f9ad9262264.png)

** Gradient Computed Without Regularization**

![image](https://user-images.githubusercontent.com/95561298/185480421-8921428f-ecd4-431b-9757-b32e092ae664.png)

** Cost Computed With Regularization**

![image](https://user-images.githubusercontent.com/95561298/185480531-288d2a82-f6bc-48e6-bda5-ba98000ecbbd.png)

** Gradient Computed With Regularization**

![image](https://user-images.githubusercontent.com/95561298/185480659-d92bd8e7-660c-4551-8133-d7289bbbefc5.png)

**New User Ratings Obtained by Collaborative Filtering**

![image](https://user-images.githubusercontent.com/95561298/185481037-535393bf-3b27-482f-a1b8-57b237a6c865.png)

**Final Prediction Results for Movies Recommended**

![image](https://user-images.githubusercontent.com/95561298/185481358-8ec974f8-a487-41c9-9283-ee655e9f46f8.png)


