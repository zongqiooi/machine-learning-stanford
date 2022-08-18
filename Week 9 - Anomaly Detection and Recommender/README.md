# K-means Clustering and Principal Component Analysis
Unsupervised Learning uses machine learning algorithms to analyze and cluster unlabeled datasets. Examples of unsupervised learning are K-means Clustering and Dimensionality reduction. K-means Clustering is an unsupervised learning algorithm that clusters the unlabeled data into K-groups. Principal Component Analysis is used for data compression to speed up learning algorithms by mapping high dimensional features x to lower dimensional representation z. This solution was created by using Octave for the Week 8 - K-means Clustering and Principal Component for Machine Learning by Andrew Ng, Stanford University. 

# Topics Covered 
- Unsupervised Learning (A type of algorithm that learns patterns from unlabelled data)
- K-means Clustering (An unsupervised learning algorithm that groups unlabelled data into K-groups)
- Dimensionality Reduction (An unsupervised learning algorithm that reduces a high dimensional features x to lower dimensional representation z)
- Principal Components Analysis (To speed up the learning algorithm, compress the data, or visualize the data)
- Random Initialization (To randomly initialize the centroid to the training data for K-means Clustering)
- Elbow Method (To identify how many clusters that have to be chosen for K-means Clustering)

# Information about K-means Clustering and Principal Component Analysis
## Part 1a: K-means Clustering
In this exercise, you will implement the K-means algorithm and use it for image compression. You will first start on an example 2D dataset that will help you gain an intuition of how the K-means algorithm works. After that, you will use the K-means algorithm for image compression by reducing the number of colors that occur in an image to only those that are most common in that image.

## Part 1b: K-means Clustering for Image Compression
In this exercise, you will use the K-means algorithm to select the 16 colors that will be used to represent the compressed image. Concretely, you will treat every pixel in the original image as a data example and use the K-means algorithm to find the 16 colors that best group (cluster) the pixels in the 3-dimensional RGB space. Once you have computed the cluster centroids on the image, you will then use the 16 colors to replace the pixels in the original image.

## Part 2a: Principal Component Analysis
In this exercise, you will use principal component analysis (PCA) to perform dimensionality reduction. You will first experiment with an example 2D dataset to get intuition on how PCA works, and then use it on a bigger dataset of 5000 face image datasets.

## Part 2b: Principal Component Analysis on Face Image Dataset
In this part of the exercise, you will run PCA on face images to see how it can be used in practice for dimension reduction. The dataset ex7faces.mat contains a dataset3 X of face images, each 32 × 32 in grayscale. Each row of X corresponds to one face image (a row vector of length 1024).

# Result of K-means Clustering and Principal Component Analysis
## Part 1a: K-means Clustering 
**Closed Centroids for K-means Clustering**

![image](https://user-images.githubusercontent.com/95561298/185307424-1cbceded-47bc-49fb-951b-64e54eb4f6f8.png)

**Centroid Means for K-means Clustering**

![image](https://user-images.githubusercontent.com/95561298/185307520-eca97351-74db-43eb-be58-75776d2767cb.png)

**K-means Clustering for the 1st Iteration**

![image](https://user-images.githubusercontent.com/95561298/185307640-44f54e2c-8378-4373-a16f-c7239b22e885.png)

**K-means Clustering for the 2nd Iteration**

![image](https://user-images.githubusercontent.com/95561298/185307798-99261020-14bf-482a-b406-59c4f706a197.png)

**K-means Clustering for the 3rd Iteration**

![image](https://user-images.githubusercontent.com/95561298/185307826-613129c0-29ef-4695-98ea-422134af4565.png)

**K-means Clustering for the 4th Iteration**

![image](https://user-images.githubusercontent.com/95561298/185307851-9b13968b-d4dc-4979-af17-fd829efd6adb.png)

**K-means Clustering for the 5th Iteration**

![image](https://user-images.githubusercontent.com/95561298/185307871-d4881dc9-d50c-4bc0-8a08-2d65bf115633.png)

**K-means Clustering for the 6th Iteration**

![image](https://user-images.githubusercontent.com/95561298/185307899-2b92ba18-c1b9-47e1-a5ec-9eb7a6d9b7ec.png)

**K-means Clustering for the 7th Iteration**

![image](https://user-images.githubusercontent.com/95561298/185307926-499f116c-b249-4bf3-82e8-66f6bb2e332f.png)

**K-means Clustering for the 8th Iteration**

![image](https://user-images.githubusercontent.com/95561298/185307942-11bc86db-5f03-44d0-8e31-b1a63bdb4c29.png)

**K-means Clustering for the 9th Iteration**

![image](https://user-images.githubusercontent.com/95561298/185307961-7f5bf71c-978a-4c3d-9939-db3bfcf52092.png)

**K-means Clustering for the 10th Iteration**

![image](https://user-images.githubusercontent.com/95561298/185307985-0d64534e-f8f0-4bdc-8f7e-56f505520e48.png)

## Part 1b: K-means Clustering for Image Compression
**Closed Centroids for K-means Clustering Image Compression**

![image](https://user-images.githubusercontent.com/95561298/185308288-a3e39d0a-2d57-4d68-9e48-87bb1f53143b.png)

**Original Image 24-bit colors and Compressed Image with 16 colors**

![image](https://user-images.githubusercontent.com/95561298/185308461-41b64f4f-3411-4781-8fd2-ad0ce3427bdc.png)

## Part 2a: Principal Component Analysis
**Plot of 2D dataset**

![image](https://user-images.githubusercontent.com/95561298/185308793-acf9b730-72da-4696-8cc1-e2132523ac1d.png)

**Eigenvectors Computed for PCA**

![image](https://user-images.githubusercontent.com/95561298/185309184-23ef5df0-c609-401b-ab0a-59d891478321.png)

**Normalized and Projected Data After PCA**

![image](https://user-images.githubusercontent.com/95561298/185309524-f51d3108-84cd-4720-9ea1-b474c26a1af8.png)

## Part 2b: Principal Component Analysis on Face Image Dataset
**Plot of Original Face Dataset**

![image](https://user-images.githubusercontent.com/95561298/185309694-63f4ce81-d9be-46ef-be51-3b5ec9aa2994.png)

**Principal Components on the Face Dataset**

![image](https://user-images.githubusercontent.com/95561298/185310156-20faaa0e-7bf0-47cc-8ebd-733fff175af4.png)

**Original Images of Faces and Projected Images of Faces From Only Top 100 Principal Components**

![image](https://user-images.githubusercontent.com/95561298/185310421-8acb5bc9-90d6-4eb7-9d76-6d288da69415.png)

**Extra**
**Original Data in 3D**

![image](https://user-images.githubusercontent.com/95561298/185312049-c0ed0654-25dd-4314-941b-5edd142a4bd5.png)

**2D Visualization Produced Using PCA**

![image](https://user-images.githubusercontent.com/95561298/185312519-16632d09-32d0-483e-bfb6-b8547a3fa104.png)









