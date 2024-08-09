### Overview

The task is to implement a K-Means clustering algorithm to categorize retail store customers based on their purchasing behavior. This clustering approach offers valuable insights for personalized marketing, customer targeting, and overall business decisions. By using customers' annual income and spending scores, the algorithm forms clusters and visualizes the results.

### Dataset

The analysis is based on a dataset that contains customer details, including attributes like 'Age,' 'Annual Income,' and 'Spending Score.' This dataset serves as the basis for training and assessing the clustering model.

**Dataset Link:** [Customer Segmentation Tutorial in Python](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

### Technologies Used

1. **Python:** The primary language for implementing the solution.
2. **NumPy:** Used for numerical computations and data handling.
3. **Matplotlib:** Utilized for data and image visualization, specifically for visualizing clustering results.
4. **scikit-learn:** Provides machine learning tools for tasks such as regression models, feature scaling, and clustering.
5. **pandas:** Employed for data manipulation and analysis.

### Code Overview

1. **Dataset Loading:** The 'Mall_Customers.csv' dataset is loaded using pandas.
2. **Feature Selection:** The features 'Annual Income (k$)' and 'Spending Score (1-100)' are chosen for clustering.
3. **Data Scaling:** The selected features are scaled using StandardScaler to ensure consistency in data magnitude.
4. **K-Means Clustering:** The K-Means algorithm is applied with a specified number of clusters (n_clusters = 5). The resulting cluster assignments are added to the dataset as a 'Cluster' column.
5. **Data Visualization:** The clustered data is represented in a scatter plot with 'Annual Income (k$)' on the x-axis and 'Spending Score (1-100)' on the y-axis, with each point color-coded according to its cluster.
6. **Output Display:** The cluster assignments are displayed, showing each customer's 'CustomerID' along with their assigned cluster.

### Project Outcome

1. **Optimal Clusters:** Five clusters were identified as optimal for customer segmentation.
2. **Insights:** The analysis uncovered distinct customer segments, which can support targeted marketing and personalized engagement.

### Conclusion

This project illustrates the use of K-Means clustering to segment customers based on their annual income and spending score. The visualizations help identify distinct customer segments, providing a foundation for further analysis and tailored marketing strategies. This code serves as a clear example of employing clustering techniques for customer segmentation.
