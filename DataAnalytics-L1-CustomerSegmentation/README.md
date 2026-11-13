# Customer Segmentation Analysis

## Project Overview
This project focuses on segmenting e-commerce customers based on their purchasing behaviour using the K-Means clustering algorithm.

RFM Analysis (Recency, Frequency and Monetary) is used to identify different customer groups and help businesses develop targeted marketing strategies.

## Objective
- Analyse customer purchasing behaviour.
- Identify meaningful customer segments.
- Apply K-Means clustering.
- Visualise customer groups.
- Recommend marketing strategies for each segment.

## Dataset
**Dataset:** Online Retail Dataset

**File:** `Online Retail.xlsx`

**Records:** 541,909

**Features:** 8 columns

The dataset contains online retail transactions, including invoice numbers, product descriptions, quantities, invoice dates, unit prices, customer IDs and countries.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Dataset Loading and Inspection
2. Data Cleaning and Preprocessing
3. Descriptive Statistics
4. RFM Analysis
5. Feature Selection
6. Data Standardisation using StandardScaler
7. Optimal Cluster Selection using Elbow Method
8. K-Means Clustering
9. Customer Segment Profiling
10. Data Visualisation
11. Business Insights and Marketing Recommendations

## RFM Analysis

Three behavioural features were selected:

- **Recency:** Number of days since the customer's last purchase.
- **Frequency:** Number of unique orders placed by the customer.
- **Monetary:** Total amount spent by the customer.

## Customer Segmentation Results

The K-Means algorithm was applied with **3 clusters**, identifying the following customer segments:

| Cluster | Number of Customers | Percentage | Segment |
|---|---:|---:|---|
| 0 | 1,082 | 24.94% | At-Risk / Inactive Customers |
| 1 | 3,230 | 74.46% | Regular Customers |
| 2 | 26 | 0.60% | High-Value Customers |

### Key Observations

- **At-Risk / Inactive Customers:** These customers have relatively high recency and lower purchasing frequency.
- **Regular Customers:** This is the largest segment, representing 74.46% of the customer base.
- **High-Value Customers:** This small segment contributes exceptionally high monetary value and deserves special attention.

These segments can help businesses design targeted marketing campaigns, improve customer retention, and build customer loyalty.

## Visualisations

The project includes:

- Elbow Method graph
- Recency vs Monetary scatter plot
- Frequency vs Monetary scatter plot
- Number of Customers per Cluster bar chart

## Business Insights and Recommendations

**Cluster 0 – At-Risk Customers**
- Low purchase frequency and spending.
- Recommended strategy: Re-engagement campaigns and personalised discounts.

**Cluster 1 – Regular Customers**
- Moderate purchasing activity.
- Recommended strategy: Loyalty programmes and repeat-purchase offers.

**Cluster 2 – High-Value Customers**
- Very high purchasing value.
- Recommended strategy: VIP rewards, exclusive offers and personalised services.

## Conclusion

Customer segmentation was successfully performed using RFM analysis and the K-Means clustering algorithm.

Three distinct customer groups were identified based on their purchasing behaviour. The analysis demonstrates how machine learning can help businesses understand customers, improve retention and develop targeted marketing strategies.

## How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn openpyxl jupyter
   ```

3. Open Jupyter Notebook.
4. Open `Customer_Segmentation_Analysis.ipynb`.
5. Run the notebook cells sequentially.

**Note:** Keep the `dataset` folder in the same project directory as the notebook so the dataset path works correctly.

---

**Project Type:** Data Analytics / Machine Learning  
**Algorithm:** K-Means Clustering  
**Technique:** RFM Customer Segmentation