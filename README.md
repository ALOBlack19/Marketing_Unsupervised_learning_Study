# Marketing_Unsupervised_learning_Study

#### Customer Segmentation with Clustering Models

## Unveiling Patterns in Marketing Campaign Data 🕵️‍♀️

Welcome to this repository! This project dives into a fascinating marketing campaign dataset, aiming to uncover hidden customer segments using various unsupervised machine learning algorithms. If you've ever wondered how large datasets can reveal distinct customer behaviors without explicit labels, this project is a hands-on exploration of that very concept.

### What's Inside?

This repository contains a Python notebook (`clustering_marketing_campaign_assignment.ipynb`) that walks through a practical application of clustering techniques. My primary goal with this project was to **practice and compare different clustering algorithms**, understanding their strengths, weaknesses, and how to optimize their performance for real-world data.

You'll find steps covering:

* **Data Loading and Preprocessing:** Handling missing values and preparing the raw data for analysis.
* **Feature Scaling:** Standardizing numerical features to ensure fair treatment by distance-based algorithms.
* **Dimensionality Reduction with PCA:** Transforming the high-dimensional dataset into a more manageable (and visually interpretable) lower-dimensional space while retaining crucial information. This was a critical step in making the data amenable to certain clustering methods.
* **Clustering Algorithms in Action:**
    * **K-Medoids:** An exploration of this partitioning algorithm, understanding its sensitivity to initial conditions and its approach to finding cluster centers.
    * **K-Means:** Another popular partitioning method, with a focus on evaluating the optimal number of clusters using the Silhouette Score.
    * **DBSCAN (Density-Based Spatial Clustering of Applications with Noise):** A deep dive into this powerful algorithm, particularly its ability to find arbitrarily shaped clusters and identify noise points. This section includes systematic parameter tuning (`eps` and `min_samples`) to achieve the best possible clustering results based on the Silhouette Score, cluster count, and noise points.

### A Curious Journey into Unsupervised Learning

This project has been an exciting journey into the nuances of unsupervised learning. It's truly intriguing to see how different algorithms interpret the same data and reveal varied structures. The process of optimizing parameters, especially for DBSCAN, has been a particularly insightful challenge.

### Let's Collaborate! 🤝

I'm constantly learning and always eager to improve. If you have any suggestions for:

* Alternative preprocessing techniques
* Different dimensionality reduction methods
* More advanced clustering algorithms
* Novel ways to evaluate clustering performance
* Or any other insights on this project!

Please don't hesitate to open an issue, submit a pull request, or reach out. I'm genuinely open to discussing any further suggestions for improvements and best practices!

---

**Technologies Used:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.