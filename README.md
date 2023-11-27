# clustercreditscoring
Clustering Credit Scoring Classifiers

This repository holds the final project information for the University of Colorado Masters of Data Science Unsupervised Algorithms Class. 

The contents include the data used, the powerpoint slides for the presentation, and the notebook. These data also exist on Kaggle here:
* Public Dataset at Kaggle (https://www.kaggle.com/datasets/clkmuhammed/creditscoreclassification)
* Original Notebook hosted at Kaggle (https://www.kaggle.com/code/toddgardiner/unsupervised-final-creditscoring)

The project illustrates;
  1. The efficacy of clustering algorithms on difficult classification tasks.
  2. The prediction limitations of some types of clustering algorithms.
     * (KMeans and Affinity Propogation can make predictions on unseen data)
     * (Agglomerative, DBSCAN, and HDBSCAN can not make predictions on unseen data)
  3. Benchmarks the clustering results against a tuned Random Forest Classifier (using Optuna)
