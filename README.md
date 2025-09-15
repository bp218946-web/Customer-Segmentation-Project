 # Customer Segmentation using RFM Analysis

## Project Overview
This project performs customer segmentation for an e-commerce company using the Online Retail dataset. The goal is to identify distinct customer groups based on their purchasing behavior using RFM (Recency, Frequency, Monetary) analysis and the K-Means clustering algorithm. The final output provides actionable marketing strategies for each customer segment.

---

## Dataset
The dataset used is the "Online Retail" dataset from the UCI Machine Learning Repository.
- **Source:** [https://archive.ics.uci.edu/dataset/352/online+retail](https://archive.ics.uci.edu/dataset/352/online+retail)

---

## Methodology
1.  **Data Cleaning:** Handled missing values, removed canceled orders and duplicates.
2.  **Feature Engineering:** Calculated Recency, Frequency, and Monetary (RFM) scores for each customer.
3.  **Clustering:** Applied K-Means clustering to segment customers based on their scaled RFM scores. The optimal number of clusters was found to be 4 using the Elbow Method.
4.  **Analysis & Visualization:** Analyzed and visualized the characteristics of each customer segment.

---

## Key Findings: Customer Segments
The analysis revealed four distinct customer personas:
- **Champions (VIPs):** Highly loyal and profitable customers who purchase frequently and recently.
- **Loyal Customers:** Active and valuable customers who are on the verge of becoming Champions.
- **Standard Customers:** The largest group, representing the average customer.
- **At-Risk Customers:** Customers who have not purchased in a long time and are at risk of churning.

---

## How to Use
1. Clone the repository.
2. Ensure you have the required libraries (pandas, scikit-learn, etc.).
3. Place the `Online Retail.xlsx` dataset in the same directory.
4. Run the `Customer_Segmentation_Analysis.ipynb` notebook.
