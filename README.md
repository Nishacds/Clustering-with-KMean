# Customer Segmentation Using K-Means Clustering
# Overview
- This project demonstrates the use of K-Means Clustering, an unsupervised machine learning algorithm, to segment customers based on their annual income and spending score. The goal is to uncover meaningful   customer groups that can help businesses personalize marketing strategies and make data-driven decisions.

# Dataset
- The analysis is based on the Mall Customer Segmentation Dataset, which includes demographic and behavioral information such as customer ID, gender, age, annual income (in thousands), and spending score (1–100).

  - Dataset Source: Kaggle – Mall Customer Segmentation Data

# Methodology
1. Data Loading and Exploration
- The dataset was loaded using Pandas, and initial visualizations were created to understand the distribution of data.
- Focused on the two key features: Annual Income and Spending Score for segmentation.

2. K-Means Clustering
- Implemented the K-Means algorithm using Scikit-learn.
- Applied clustering to group customers and assigned cluster labels accordingly.

3. Optimal Number of Clusters: Elbow Method
- sed the Elbow Method by plotting the inertia (sum of squared distances) to determine the ideal number of clusters.

4. Cluster Visualization
- Visualized clusters using a 2D scatter plot with clear color distinctions for each cluster.
- Displayed the centroids of each cluster to show the center of each segment.

5. Clustering Evaluation
- Evaluated clustering performance using the Silhouette Score, which resulted in a score of 0.55, indicating reasonable cluster separation.

# Results
- The clustering analysis identified distinct customer groups based on spending behavior and income levels. These insights can be used by businesses to develop targeted marketing campaigns, customize services,   and improve customer engagement strategies.

# Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook
