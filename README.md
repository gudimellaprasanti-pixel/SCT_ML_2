# Customer Segmentation using K-Means Clustering

## Overview
This project uses the K-Means Clustering algorithm to segment customers of a retail store based on their purchasing behavior. Customer segmentation helps businesses understand different customer groups and create targeted marketing strategies.

## Objective
To group customers into distinct clusters based on:
- Annual Income
- Spending Score

using the K-Means Clustering algorithm.

## Dataset
The dataset contains customer information such as:

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

Dataset: Mall_Customers.csv

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Steps Performed

### 1. Data Loading
Loaded the customer dataset using Pandas.

### 2. Feature Selection
Selected:
- Annual Income (k$)
- Spending Score (1-100)

for clustering.

### 3. Elbow Method
Used the Elbow Method to determine the optimal number of clusters (K).

### 4. K-Means Clustering
Applied K-Means with K = 5 to segment customers.

### 5. Visualization
Visualized clusters and centroids using scatter plots.

### 6. Cluster Analysis
Analyzed customer groups based on income and spending behavior.

## Results

The customers were divided into 5 clusters:

| Cluster | Description |
|----------|------------|
| Cluster 1 | Average Income, Average Spending |
| Cluster 2 | High Income, High Spending |
| Cluster 3 | Low Income, High Spending |
| Cluster 4 | High Income, Low Spending |
| Cluster 5 | Low Income, Low Spending |

## Output

### Elbow Method
Determines the optimal number of clusters.

### Customer Segmentation Plot
Displays customer groups and cluster centroids.

## Conclusion

K-Means Clustering successfully segmented customers into meaningful groups based on their annual income and spending score. These insights can help businesses improve marketing strategies, customer retention, and personalized recommendations.



## How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/SCT_ML_2.git
```

2. Install required libraries

```bash
pip install pandas numpy matplotlib scikit-learn
```

3. Run the Python file

```bash
python welcome_to_colab.py
```

## Author

Bhavya Prasanti

SkillCraft Technology - Machine Learning Internship Task 02
