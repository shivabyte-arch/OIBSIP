Task1 : Supermart Sales Analysis

## Project Overview:
This project performs Exploratory Data Analysis (EDA) on retail sales data using Microsoft Excel.  
The goal is to analyze sales trends, identify top-performing categories and cities, and generate meaningful business insights.

## Tasks Completed:
- Data Cleaning
- Sales by Category Analysis
- Sales by City Analysis
- Time Series Analysis (Sales Trend Over Time)
- Data Visualization using Charts
- Insights and Recommendations

## Tools Used:
- Microsoft Excel
- Pivot Tables
- Charts (Bar Chart, Line Chart)

## Key Insights:
- Sales show a consistent upward trend from 2015 to 2018, indicating strong business growth.
- The "Eggs, Meat & Fish" category generates the highest revenue among all product categories.
- Kanyakumari and Vellore are the top-performing cities in terms of sales.
- Sales peak during the September to December period, indicating strong seasonal demand.
- Lower sales are observed in the beginning months (January–February), suggesting seasonal variation.

## Recommendations:
- Focus marketing campaigns during peak months (September–December) to maximize revenue.
- Increase inventory for high-performing categories like Eggs, Meat & Fish and Snacks.
- Improve sales strategies in mid- and low-performing cities to boost overall revenue.
- Use seasonal trends to plan discounts, offers, and promotional campaigns.
- Analyze customer behavior further to personalize marketing strategies.

## Conclusion:
The analysis reveals a clear growth trend in sales along with seasonal patterns and regional performance differences.  
By leveraging these insights, businesses can make data-driven decisions to improve sales, optimize inventory, and enhance overall performance.



Task2 : Fraud Detection using Machine Learning 

##Project Overview :
This project focuses on detecting fraudulent credit card transactions using machine learning techniques.  
The dataset is highly imbalanced, making fraud detection a challenging task.

## Dataset:
- Contains anonymized credit card transactions  
- Features are transformed using PCA  
- Target variable:
  - 0 → Normal Transaction  
  - 1 → Fraudulent Transaction  

## Tasks Performed:
1.Data Analysis :
- Checked class distribution  
- Visualized imbalance using plots
  
2.Handling Imbalance :
- Applied Upsampling to balance fraud and normal classes
   
3.Feature Engineering : 
- Created new features from transaction amount  
- Applied scaling for normalization
   
4.Model Building :
- Used Logistic Regression for classification
  
5.Model Evaluation :
- Evaluated using
  - Confusion Matrix  
  - Classification Report 
- Focused on Recall for fraud detection
  
6.Anomaly Detection :
- Implemented Isolation Forest  
- Identified unusual transaction patterns
  
7.Real-Time Simulation :
- Simulated prediction on new transaction data  
- Classified as fraud or normal instantly  

## Technologies Used:
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

## Results:
- Achieved high recall for fraud detection  
- Successfully identified most fraudulent transactions  
- Demonstrated effectiveness on imbalanced dataset

## Dataset:
Dataset is provided in compressed ZIP format.
Steps to use:
1. Download the ZIP file
2. Extract it
3. Use `creditcard.csv` in the notebook

## Conclusion:
This project demonstrates how machine learning can effectively detect fraudulent transactions.  
Handling class imbalance and focusing on recall significantly improves fraud detection performance.



##Task3: Customer Segmentation using K-Means

## Project Overview:
This project focuses on customer segmentation using K-Means clustering. The goal is to group customers based on their purchasing behavior and demographics to help businesses improve marketing strategies.

## Dataset:
The dataset contains customer information such as:
- Income
- Age
- Purchase behavior
- Product spending
  
## Steps Performed:
1.Data Collection
Loaded the dataset using pandas.

2.Data Exploration
Analyzed dataset structure using `.head()`, `.info()`, `.describe()`.

3.Feature Engineering
Created new features:
- Total Spending (MntTotal)
- Total Purchases
- Engagement Rate

4.Data Preprocessing
Scaled features using StandardScaler.

5.Clustering
Applied K-Means algorithm to segment customers into groups.

6.Visualization
Visualized clusters using scatter plots.

7.Insights
Identified different customer groups based on income and spending behavior.

## Results:
- High-value customers identified
- Low engagement customers identified
- Useful segmentation for marketing strategies
  
## Technologies Used:
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
  
## Conclusion:
Customer segmentation helps businesses understand customer behavior and improve targeted marketing.

