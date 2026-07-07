# Online Retail Customer Analytics & Segmentation

## Project Overview
This Capstone project focuses on analyzing transactional data from a UK-based online retail company. The goal is to perform Exploratory Data Analysis (EDA) to extract business insights and apply Machine Learning (K-Means Clustering) to segment customers based on their purchasing behavior using RFM (Recency, Frequency, Monetary) analysis.

## Objectives
- Clean and preprocess transactional data (handling missing values, cancellations, and duplicates).
- Perform deep EDA to uncover seasonal trends, peak sales hours, and geographical dominance.
- Engineer RFM features for customer behavior profiling.
- Build a K-Means clustering model to segment customers into actionable business tiers.
- Provide strategic business recommendations based on the segments.

##  Dataset
- **Source:** [UCI Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)
- **Context:** Transactions occurring between Dec 2010 and Dec 2011 for a UK-based and registered non-store online retail.

##  Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Algorithms:** K-Means Clustering (evaluated using the Elbow Method)

## Key Findings & Customer Segments
Through RFM analysis and K-Means ($K=4$), we identified four distinct customer groups:
1. **VIP / Champions:** High spenders, frequent buyers, and recently active.
2. **Loyal Customers:** Consistent buyers with strong monetary value.
3. **Active / General Market:** The majority of the customer base with average spending and moderate recency.
4. **Churned / Lost:** Customers who have not made a purchase in over 8 months.

## Business Recommendations
- Provide dedicated account managers and exclusive perks for **VIPs** to ensure retention.
- Target the **General Market** with seasonal discounts during peak hours (10 AM - 3 PM) to increase transaction frequency.
- Deploy aggressive win-back campaigns for **Churned** customers.
- Optimize inventory for Q4 holidays and consider weekend (Saturday) operations to capture lost sales.

## Repository Structure
- `/data`: Contains the dataset (or a link to it).
- `/notebooks`: Jupyter Notebook containing the full code (Cleaning, EDA, ML).
- `/presentation`: The final presentation slides summarizing the project.
