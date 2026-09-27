# SmartCart Customer Segmentation

## Project Overview

SmartCart Customer Segmentation is an unsupervised machine learning project that analyzes customer data and groups customers into meaningful segments based on their characteristics and purchasing behavior.

The project follows a customer-segmentation workflow including data preprocessing, feature engineering, exploratory analysis, outlier handling, categorical encoding, feature scaling, dimensionality reduction, and clustering.

## Dataset

The dataset contains customer demographic, purchasing, and campaign-related information.

**Dataset file:** `smartcart_customers.csv`

## Project Workflow

1. Load the customer dataset
2. Explore the data and check missing values
3. Handle missing values
4. Perform feature engineering
5. Create customer features such as:

   * Age
   * Customer tenure
   * Total spending
   * Total children
   * Living-with status
6. Prepare the data for clustering
7. Detect and handle outliers
8. Encode categorical variables
9. Scale numerical features
10. Apply PCA for dimensionality reduction
11. Determine a suitable number of clusters
12. Apply K-Means clustering
13. Apply Agglomerative Clustering
14. Analyze and visualize customer segments

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Kneed
* Jupyter Notebook

## Project Files

```text
SmartCart-Customer-Segmentation/
│
├── smartcart.ipynb
├── smartcart_customers.csv
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook smartcart.ipynb
```

Run the notebook from the first cell onward.

## Project Objective

The objective of this project is to use unsupervised machine learning to identify groups of customers with similar characteristics and purchasing behavior. These customer segments can support customer analysis and targeted marketing strategies.

## Author

Aryan Mane
