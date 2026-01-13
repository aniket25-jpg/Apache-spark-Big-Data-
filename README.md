This project performs customer segmentation on large-scale e-commerce data using Apache Spark (PySpark). It applies RFM (Recency, Frequency, Monetary) analysis to understand customer behavior and uses K-Means clustering to segment customers into meaningful business groups such as:
Champions (High-value loyal customers)
At-Risk / Churned customers
Regular / Potential customers
The project demonstrates how big data analytics can be used to drive data-driven marketing and business strategies.

🎯 Objectives

-> Analyze historical transaction data at scale
-> Compute RFM metrics for each customer
-> Perform feature engineering, log transformation, and scaling
-> Apply K-Means clustering for customer segmentation
-> Interpret clusters and derive business strategies

🛠️ Workflow

-> Data loading and cleaning using PySpark
-> RFM feature engineering
-> Log transformation to handle skewness
-> Feature scaling (Standardization)
-> Finding optimal K using Elbow method
-> K-Means clustering
-> Cluster interpretation and visualization
-> Business strategy recommendations

📊 Customer Segments

-> Champions – Recent, frequent, high spenders
-> Regular / Potential – Good engagement, growth potential
-> At-Risk / Churned – Low engagement, low spending

🧰 Tech Stack

-> Python

-> PySpark (Apache Spark)

-> Pandas, NumPy

-> Matplotlib / Seaborn

-> Scikit-learn


📈 Business Impact

-> Enables targeted marketing campaigns
-> Improves customer retention
-> Helps increase revenue
-> Identifies high-value customers
