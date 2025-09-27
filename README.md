# Core Machine Learning Exploration

A hands-on journey through classical machine learning algorithms using the MovieLens 100k dataset. This notebook covers regression, classification, clustering, dimensionality reduction, ensemble methods, recommendation systems, and perceptrons — all with detailed comments on key hyperparameters for learning purposes.

**Goal:** Understand and experiment with fundamental ML algorithms on a real-world dataset.

## ML Concepts and Algorithms Explored:

This notebook covers the following key machine learning areas and algorithms:

*   **Regression:**
    *   Linear Regression
    *   Ridge Regression
    *   Lasso Regression
*   **Classification:**
    *   Logistic Regression
    *   k-Nearest Neighbors (KNN)
    *   Decision Tree
    *   Random Forest
    *   Gradient Boosting (using scikit-learn, XGBoost, and LightGBM)
    *   Support Vector Machines (SVM)
*   **Clustering (Unsupervised Learning):**
    *   K-Means
    *   Hierarchical Clustering
    *   DBSCAN
*   **Dimensionality Reduction / Feature Extraction:**
    *   Principal Component Analysis (PCA)
    *   t-SNE / UMAP (for visualization)
*   **Ensemble Methods:**
    *   Bagging
    *   Boosting (AdaBoost, Gradient Boosting)
*   **Recommendation / Latent Factor Models:**
    *   Matrix Factorization (SVD - *Note: Code is commented out due to dependency issues in this environment*)
    *   Collaborative Filtering (*Note: Code is commented out due to dependency issues in this environment*)
*   **Perceptron (Bridge to Deep Learning):**
    *   Single-Layer Perceptron

## Summary

This notebook provides a practical walkthrough of major classical ML algorithms, offering hands-on experience and insights into key hyperparameters. It serves as a foundation for understanding core ML concepts and prepares the learner for more advanced topics.

## How to Run the Notebook:

1.  Clone this repository to your local machine or open it directly in Google Colab.
2.  If running in Colab, the notebook will automatically download the MovieLens 100k dataset.
3.  Run the cells sequentially.
4.  *(Note: The sections on Recommendation Systems using the `surprise` library are commented out due to potential dependency conflicts with newer NumPy versions. You can attempt to uncomment and run them at your own risk, or explore alternative recommendation libraries.)*

## Dependencies:

The notebook requires the following libraries (most are pre-installed in Colab):

*   pandas
*   numpy
*   scikit-learn
*   matplotlib
*   umap-learn (if running the UMAP section)
*   xgboost (if running the XGBoost section)
*   lightgbm (if running the LightGBM section)
*   surprise (Optional, code commented out)

## Learning Outcomes

* A beginner-level understanding of the theory and intuition behind major classical ML algorithms.  
* Hands-on experience with Regression, Classification, Clustering, Dimensionality Reduction, Ensemble Methods, Recommendation Systems, and Perceptrons.
* Serves as a bridge to more advanced topics, such as neural networks and deep learning.

- 🗿 This notebook was created as a personal learning project. Explanations and guidance were supplemented with resources including ChatGPT and official documentation.
