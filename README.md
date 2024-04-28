# 5-project-for-ML

THIS PROJECT NEEDS SOME MODIFICATIONS BECAUSE IT IS NOT FINISHED YET!!

This project is divided into two parts: "I. Про MNIST-подобные данные" and "II. На реальных данных."

In the first part, the code utilizes the Fashion-MNIST dataset and performs dimensionality reduction using Principal Component Analysis (PCA). It begins by importing necessary libraries and fetching the Fashion-MNIST dataset. Then, it preprocesses the data, flattening the images into one-dimensional arrays and applying PCA to reduce the dimensionality to 50 principal components. The cumulative explained variance percentage and the explained variance by the number of principal components are visualized. Next, K-Means clustering is applied to the reduced data, and the optimal number of clusters is evaluated using the Elbow method and Silhouette Score. The relationship between clusters and image labels is analyzed, and the average Silhouette Score is calculated to assess the clustering quality.

In the second part, the code works with real-world data related to car prices in Moldova. It begins by reading the dataset and performing data exploration, including data cleaning, visualization, and correlation analysis. Then, K-Means clustering is applied to the numeric features of the dataset. The results are visualized through scatter plots, histograms, and heatmaps, showing the relationship between numeric columns, car prices, and clusters. Additionally, the distribution of clusters for each car make and the probability of car styles in each cluster are analyzed. Finally, Principal Component Analysis (PCA) is applied to reduce the dimensionality of the numeric features, and the results are visualized through a scatter plot.

Overall, the project demonstrates the application of dimensionality reduction techniques like PCA and clustering algorithms like K-Means to analyze and explore high-dimensional datasets, showcasing their utility in real-world scenarios such as image classification and market segmentation.
