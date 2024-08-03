# Assignment 8
## Clustering Analysis

## Overview
This Assignment involves performing clustering analysis using three different clustering techniques: Hierarchical Clustering, K-Means Clustering, and DBSCAN. The goal is to classify customer data from East-West Airlines into similar groups based on flying patterns, earnings, use of frequent flyer rewards, and credit card usage.

## Folder Structure
- `README.md`: This file, providing an overview and instructions.
- `Clustering analysis.docx`: A document explaining the assignment problem in detail.
- `EastWestAirlines.xlsx`: The dataset used for clustering analysis.
- `Assignment_8.ipynb`: The Jupyter Notebook containing the code and analysis.

## Dataset
The dataset is provided by East-West Airlines and contains the following attributes:
- **ID#:** Unique identifier for each customer.
- **Balance:** The number of miles eligible for award travel.
- **Qual_miles:** Miles counted as qualifying for Topflight status.
- **cc1_miles:** Miles earned with frequent flyer credit card in the past 12 months.
- **cc2_miles:** Miles earned with Rewards credit card in the past 12 months.
- **cc3_miles:** Miles earned with Small Business credit card in the past 12 months.
- **Bonus_miles:** Miles earned from non-flight bonus transactions in the past 12 months.
- **Bonus_trans:** Number of non-flight bonus transactions in the past 12 months.
- **Flight_miles_12mo:** Number of flight miles in the past 12 months.
- **Flight_trans_12:** Number of flight transactions in the past 12 months.
- **Days_since_enroll:** Number of days since the customer enrolled.
- **Award?:** A dummy variable indicating whether the customer received the last award (1=not null, 0=null).

## Objective
To perform different clustering techniques (Hierarchical Clustering, K-Means Clustering, DBSCAN) on the given data and classify the data into similar groups.

## Clustering Techniques
### 1. Hierarchical Clustering
- Performed and visualized dendrograms.
- Formed clusters and interpreted them.

### 2. K-Means Clustering
- Applied the K-Means algorithm.
- Determined the optimal number of clusters using the elbow method.
- Visualized and interpreted the clusters.

### 3. DBSCAN Clustering
- Implemented DBSCAN to identify outliers and clusters.
- Provided interpretations of the results.

## Summary and Interpretation
### Hierarchical Clustering
- Formed two clusters and interpreted them based on their attributes.

### K-Means Clustering
- Classified the data into four different groups and provided visualizations and interpretations.

### DBSCAN Clustering
- Identified outliers and two distinct groups.

## Conclusion
The assignment provides insights into the customer segments of East-West Airlines. Each clustering technique offers a different perspective:
- **Hierarchical Clustering:** Two main clusters were identified.
- **K-Means Clustering:** Four clusters provided a more detailed segmentation.
- **DBSCAN Clustering:** Identified outliers and distinct groups, useful for spotting unusual behaviors.

## How to Use
1. Open `Assignment_8.ipynb` using Jupyter Notebook.
2. Ensure that the dataset `EastWestAirlines.xlsx` is in the same directory as the notebook.
3. Run the notebook cells to perform the clustering analysis and visualize the results.
4. Refer to `Clustering analysis.docx` for a detailed explanation of the problem and methodology.

## Requirements
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

Install the required packages using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
