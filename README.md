# Customer-Segmentation-KMeans
Customer Segmentation using K-Means Clustering in Python
Customer Segmentation Using K-Means Clustering

1. Introduction
Customer segmentation is a Machine Learning technique used to divide customers into different groups based on their behaviour and characteristics.

This project uses the K-Means Clustering algorithm to group mall customers based on annual income and spending score.

2. Problem Statement
Businesses have many customers with different spending habits. Understanding these customers helps businesses improve their marketing strategies.

This project uses K-Means to identify groups of customers with similar spending patterns.

3. Objectives
- Understand customer spending behaviour.
- Group similar customers.
- Implement K-Means clustering using Python.
- Find a suitable number of clusters.
- Evaluate clustering performance.
- Visualize the final results.

4. Dataset
Dataset name:** Mall Customer Segmentation

Source:** [Kaggle Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

Features used:
- Annual Income (k$)
- Spending Score (1-100)

5. Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

6. Algorithm Used
K-Means is an unsupervised Machine Learning algorithm that divides data into K clusters based on similarity.

The algorithm assigns data points to their nearest cluster centroid and repeatedly updates the centroids.

7. Implementation Steps
1. Import Python libraries.
2. Load the dataset.
3. Check missing and duplicate values.
4. Select important features.
5. Apply feature scaling.
6. Use the Elbow Method.
7. Calculate Silhouette Scores.
8. Train the K-Means model.
9. Visualize customer clusters.
10. Compare optimization settings.

8. Optimization Techniques
- StandardScaler for feature scaling.
- Elbow Method for selecting the number of clusters.
- Silhouette Score for evaluating cluster quality.
- Comparison of different n_init values.
- Fixed random state for reproducibility.

9. Results
**Selected K:** [5]
**Silhouette Score:** [0.5547]
**Inertia:** [65.5684]

The model groups customers according to their annual income and spending behaviour.

10. Overfitting and Underfitting Analysis
K-Means is an unsupervised learning algorithm, so traditional supervised learning overfitting and underfitting tests do not directly apply.

Too few clusters may combine different customer groups, while too many clusters may create unnecessary groups.

The Elbow Method and Silhouette Score help identify a suitable clustering solution.

11. Real-Life Applications
- Shopping malls.
- E-commerce websites.
- Retail businesses.
- Customer relationship management.
- Targeted marketing.

12. Conclusion
This project demonstrates how K-Means clustering can identify different customer groups based on income and spending patterns.

The results can help businesses understand customer behaviour and improve marketing decisions.

13. Future Scope
- Use more customer features.
- Experiment with other clustering algorithms.
- Use larger datasets.
- Develop an interactive customer segmentation dashboard.

14. How to Run the Project
1. Download the project repository.
2. Open Google Colab.
3. Upload the Python notebook.
4. Upload the Mall_Customers.csv dataset.
5. Execute the notebook cells in order.

15. Project Author
Student Name:  Armaan Raj

Student ID: 241001001267

Subject: Machine Learning Theory Assignment
