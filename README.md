# K-Means Clustering: Mall Customer Segmentation

This repository contains the solution to Task 8 of the AI & ML Internship: using K-Means clustering for customer segmentation based on annual income and spending score.

The categorization was done using an unsupervised learning method on the popularly known Mall Customers dataset from Kaggle, clustering the customers into 5 clusters based on the implementation. The Elbow method has been used to find the optimal number of clusters and the model was evaluated using the silhouette score.

**Main steps:**
- Loaded and pre-processed the dataset
- Used `StandardScaler` for normalizing the data
- Used the Elbow method to find the best value of `k`
- Fitted K-Means for `k=5` (from the elbow curve)
- Calculated the silhouette score (0.55)
- Prepared a nice plot using Seaborn for the final clusters

The notebook runs smoothly without any error or warning (I had to set `n_init=10` in KMeans to get rid of a warning that would pop up in the near future). The notebook contains all code, outputs, and plots.

 **Dataset used:**  
[Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
