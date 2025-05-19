
### 🛍️ Customer Segmentation using Unsupervised Learning

#### **📌 Overview**

This project performs customer segmentation based on purchasing behavior, demographics, and lifestyle features. The segmentation helps businesses develop targeted marketing strategies.

#### ** 1. Data Preprocessing**

*  Loaded dataset `customer_segmentation.csv`
*  Removed null values
*  Converted `Dt_Customer` column to datetime
*  Calculated how long the customer has been with the company


#### **📊 2. Exploratory Data Analysis (EDA)**

*  Analyzed distribution of key variables (Age, Income, Spending Score, etc.)
*  Visualized trends and patterns using matplotlib and seaborn


#### **📦 3. Feature Engineering**

*  Scaled numerical features
*  Created new features such as total spend, average spend, and customer tenure

#### ** 4. Modeling - KMeans Clustering**

*  Applied KMeans clustering algorithm
*  Used the Elbow Method to find the optimal number of clusters
*  Clustered customers into groups based on similarities

---

#### **📌 5. Results & Insights**

*  Identified distinct customer segments (e.g., high spenders, budget-conscious, new customers)
*  Recommendations for personalized marketing strategies
