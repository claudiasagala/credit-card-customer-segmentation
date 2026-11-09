# Credit Card Customer Segmentation Using K-Means Clustering

## Project Overview

This project focuses on segmenting credit card customers based on their transaction behavior and financial characteristics using the K-Means Clustering algorithm.

The objective is to identify groups of customers with similar behavioral patterns to gain insights into customer characteristics and demonstrate the application of unsupervised machine learning in financial data analysis.

## Dataset

- **Number of records:** 8,950 customer records
- **Domain:** Credit card customer behavior
- **Data characteristics:** Customer balance, purchase behavior, cash advance behavior, and other available numerical features.

## Tools and Technologies

- Python
- Google Colab
- K-Means Clustering
- Data Analysis and Visualization

## Project Workflow

The project was conducted through the following stages:

1. **Exploratory Data Analysis (EDA)**  
   Examined the dataset to understand data distributions, relationships, and customer behavior patterns.

2. **Data Preprocessing**  
   Handled missing values and outliers, selected relevant features, and standardized the data before clustering.

3. **Determining the Number of Clusters**  
   Applied the Elbow Method to determine an appropriate number of clusters.

4. **K-Means Clustering**  
   Applied the K-Means algorithm to group customers into three clusters based on their characteristics.

5. **Model Evaluation**  
   Evaluated the clustering results using the Silhouette Score.

## Results

The analysis produced three customer clusters with different characteristics based on balance, purchase behavior, and cash advance activity.

The clustering evaluation achieved a **Silhouette Score of 0.4912**, indicating a moderate degree of cluster separation.

## Repository Structure

```text
credit-card-customer-segmentation/
│
├── README.md
└── credit_card_customer_segmentation.ipynb
```

## Conclusion

This project demonstrates the use of K-Means Clustering to identify customer segments based on credit card usage patterns. The results provide an initial overview of customer behavior and illustrate how unsupervised machine learning can support exploratory analysis in the financial sector.

---

**Project Type:** Individual Academic Project  
**Author:** Claudia Sabattini Sagala
