Customer Segmentation using K-Means Clustering

This project focuses on segmentation of mall customers using K-Means clustering, aiming to identify distinct customer groups based on their 
annual income and spending patterns. The insights can guide marketing, retention, and product strategies to enhance profitability and customer satisfaction.

1. Data Overview

Dataset Size: ~200 customers.
Key Variables: Gender, Age, Annual Income (k$), Spending Score (1–100).

Preprocessing:

Dropped CustomerID (non-analytical field).
Verified no missing values.
Selected Annual Income and Spending Score for clustering.

2. Clustering Methodology

Technique Used: K-Means Clustering.
Elbow Method: Optimal number of clusters = 5.
Evaluation Metric: Within-Cluster Sum of Squares (WCSS).


3. Customer Segments Identified

Based on the analysis, customers were divided into 5 distinct clusters:

1. Cluster 1 – High Income, High Spending ("Luxury Enthusiasts")

Share: ~20% of total customers.
Characteristics: Wealthy, spend actively on premium products/services.
Business Impact: Most valuable group – direct contributors to high revenue.

2. Cluster 2 – High Income, Low Spending ("Cautious Wealthy")

Share: ~15%.
Characteristics: Affluent but conservative in spending.
Business Opportunity: Potential to increase engagement with personalized luxury campaigns.

3. Cluster 3 – Mid Income, Mid Spending ("Average Mainstream")

Share: ~35%.
Characteristics: Balanced group, moderate spenders, stable base.
Business Impact: Important for steady revenue, responsive to seasonal offers.

4. Cluster 4 – Low Income, High Spending ("Budget Dreamers")

Share: ~15%.
Characteristics: Limited income but aspirational spenders.
Business Opportunity: Target with affordable luxury and installment-based products.

5. Cluster 5 – Low Income, Low Spending ("Minimalists")

Share: ~15%.
Characteristics: Least profitable, minimal shopping activity.
Business Strategy: Limited marketing investment; focus only on cost-effective promotions.

4. Visual Insights

Elbow Curve: Confirmed 5 optimal clusters.
Scatter Plots: Showed clear separations among customer groups.
Heatmaps: Validated correlations, highlighting income vs. spending as the strongest segmentation criteria.

5. Business Implications

Targeted Marketing:
Luxury campaigns for Cluster 1 (20%).
Engagement strategies for Cluster 2 (15%).

Revenue Growth:

55% of customers (Clusters 1 + 3 + 4) show strong potential for revenue maximization.

Resource Allocation:

Reduce efforts on Cluster 5 (15%) to optimize ROI.

Customer Loyalty Programs:
Introduce reward systems to retain Cluster 1 and 3.

Conclusion:
The clustering analysis provides a data-driven roadmap for customer-centric strategies. With 5 well-defined customer personas, businesses can optimize marketing spends,
product positioning, and customer engagement to drive higher revenue and loyalty.
