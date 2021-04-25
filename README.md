# thinkful_25.6_assignment - Rob Harris

Gaussian Mixture Method (GMM) - Clustering

In this assignment, you'll continue working with the heart disease dataset from the UC Irvine Machine Learning Repository.
1. Apply GMM to the heart disease dataset by setting n_components=2. Get ARI and silhouette scores for your solution and compare it with those of the k-means and hierarchical clustering solutions that you implemented in the previous checkpoint assignments. Which algorithm performs best?
2. GMM implementation of scikit-learn has a parameter called covariance_type. This parameter determines the type of covariance parameters to use. There are four types that you can specify:
-full: This is the default. Each component has its own general covariance matrix
-tied: All components share the same general covariance matrix. diag: Each component has its own diagonal covariance matrix.
-diag: Each component has its own diagonal covariance matrix.
-spherical: Each component has its own single variance.

Try all of these. Which one performs best in terms of ARI and silhouette scores?


