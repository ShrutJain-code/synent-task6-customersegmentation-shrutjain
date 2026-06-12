# Customer Segmentation using K-Means Clustering

## Problem Statement

Businesses often have customers with different purchasing behaviors and spending patterns. Treating all customers the same can reduce the effectiveness of marketing strategies. The objective of this project is to segment customers into distinct groups based on their annual income and spending behavior using K-Means Clustering. These segments can help businesses understand their customers better and create targeted marketing campaigns.

## Dataset

The Mall Customer Dataset contains customer information collected from a shopping mall. The dataset includes:

* Customer ID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1–100)

The dataset is used to identify customer groups based on spending habits and income levels.

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## Approach

### 1. Data Loading

The dataset was loaded into a Pandas DataFrame for analysis.

### 2. Data Cleaning

* Checked for missing values
* Verified duplicate records
* Renamed columns for easier handling

### 3. Exploratory Data Analysis (EDA)

Several visualizations were created to understand:

* Age distribution
* Annual income distribution
* Spending score distribution

### 4. Feature Selection

Annual Income and Spending Score were selected as the primary features for customer segmentation.

### 5. Elbow Method

The Elbow Method was used to determine the optimal number of clusters for K-Means Clustering.

### 6. K-Means Clustering

Customers were grouped into different clusters based on their spending patterns and income levels.

### 7. Cluster Visualization

Clusters were visualized using a scatter plot to clearly identify customer segments and cluster centroids.

## Results

The K-Means algorithm successfully divided customers into five distinct groups. Each cluster represents customers with similar purchasing behavior and financial characteristics.

The visualization clearly shows separation between different customer groups, making it easier to understand customer behavior.

## Key Insights

* High-income and high-spending customers represent the most valuable customer segment.
* High-income but low-spending customers can be targeted with personalized offers and promotions.
* Low-income and low-spending customers contribute less to overall revenue.
* Customer segmentation helps businesses improve marketing efficiency and customer engagement.
* Different customer groups require different business strategies for better results.

## Conclusion

Customer segmentation using K-Means Clustering provides valuable insights into customer behavior. By grouping customers with similar characteristics, businesses can make data-driven decisions and design more effective marketing campaigns. The project demonstrates how machine learning can be used to solve real-world business problems.

## Author

Shrut Jain

Data Science Internship Program – Synent Technologies
