# SCT_ML_02
Create a k-means clustering algorithm to group customers of a retail store based on their purchase history
 1. Objective:
   Use K-Means clustering to group retail customers based on their purchase behavior for targeted marketing.
2. Tools Used:
   - Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
3. Steps:
 Step 1: Data Preparation
    - Load and clean customer purchase data (handle missing values, duplicates).
- Select relevant features such as total spend, purchase frequency, recency.
 Step 2: Feature Scaling
    - Normalize features using StandardScaler or MinMaxScaler to ensure equal weighting.
Step 3: Determine Optimal Clusters (k)
   - Use Elbow Method by plotting WCSS vs k to identify the ideal number of clusters.
 Step 4: Train K-Means Model
    - Initialize KMeans with chosen k.
   - Fit model to data to assign cluster labels to each customer.
 Step 5: Analyze Clusters
    - Examine cluster centers and summary statistics to interpret customer segments.
    - Visualize clusters using scatter plots or dimensionality reduction (PCA).
 Step 6: Business Insights
    - Use cluster information to develop targeted marketing strategies.
    - Identify high-value, frequent, and occasional customers for personalized offers.
 Outcome:
    - Customers grouped into meaningful segments to improve marketing effectiveness and sales.
