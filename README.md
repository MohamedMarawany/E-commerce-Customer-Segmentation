E-commerce Customer Segmentation

📌 Project Overview

This project focuses on analyzing e-commerce customer behavior using transactional data. The goal is to segment customers based on demographics and transaction history, enabling businesses to optimize marketing strategies and customer retention.

📊 Data Overview

The dataset consists of multiple tables, including:

Customers: Customer IDs, gender, city, and join dates.

Transactions: Coupon transactions with timestamps and status.

Branches & Merchants: Branch and merchant identifiers.

Cities & Genders: Mapping tables for better understanding.

🚀 Key Objectives

Dashboard for Stakeholders (Power BI):

Customer demographics (gender, city distributions)

Coupon usage trends (claimed vs. burned over time)

Top-performing cities and branches

Customer retention and loyalty insights

Customer Segmentation (Unsupervised Learning):

Clustering techniques: K-Means, DBSCAN, and Hierarchical Clustering

Evaluations using Silhouette Score & Davies-Bouldin Score

Segment analysis for marketing strategies

📈 Methodology

🔹 Data Preprocessing

Merging multiple tables into a single dataset.

Handling missing values and ensuring data consistency.

Standardizing numerical features for clustering.

🔹 Machine Learning Approach

Feature Selection: Using demographics & transactional data.

Modeling:

K-Means Clustering (optimized cluster selection)

DBSCAN (density-based clustering)

Hierarchical Clustering (dendrogram analysis)

Evaluation Metrics:

Silhouette Score: Measures clustering quality.

Davies-Bouldin Score: Evaluates intra-cluster variance.

🔍 Key Findings

Identified distinct customer segments based on transaction behavior.

Found key locations and branches with the highest coupon usage.

Suggested targeted marketing strategies for different customer groups.

📂 Repository Structure

📂 E-commerce-Customer-Segmentation
 ├── ecommerce_analysis.ipynb  # Jupyter Notebook with all analysis
 ├── ecommerce_cleaned_data.csv  # Processed dataset
 ├── README.md  # Project documentation
 ├── PowerBI_Dashboard.pbix  # Power BI Dashboard file

📌 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/E-commerce-Customer-Segmentation.git
cd E-commerce-Customer-Segmentation

Open ecommerce_analysis.ipynb in Jupyter Notebook and run the code.

Import ecommerce_cleaned_data.csv into Power BI to explore the dashboard.

📝 Contributors

Your Name - Machine Learning Engineer

Team Members (if any)

📅 Submission Deadline

March 6th, 11:59 PM

📧 For any queries, reach out at [your email]

