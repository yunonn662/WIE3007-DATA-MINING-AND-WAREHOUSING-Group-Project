# WIE3007 DATA MINING AND WAREHOUSING Group Assignment 2023/2024 Semester 1
## Project Introduction:
This project is part of a group assignment for the Data Mining and Warehousing (WIE3007) course at Universiti Malaya, led by Dr. Teh Ying Wah. XML and project files from various tools that are used in our analysis of the Hotel booking demand dataset, a public reservation dataset that contains 5 different tables of data and user navigation traffic dataset. Our project conducted a comprehensive analysis of hotel bookings, aiming to gain profound insights into various facets of the hospitality industry using SEMMA Methodology and various tools.

## Techniques and Tools Employed:
1. **Star Schema**: Implemented `Python Featuretools` and performed Deep Feature Synthesis (DFS) on all 5 tables of data, then suitable features are selected and a star schema was designed.
2. **ETL Process**: All 5 tables of data with added features are then combine into one huge consolidated table that can be used for SEMMA Methodology using Talend Open Studio for Data Integration.
3. **Data Preparation**: StatExplore Node in SAS EM is used to obtain an overview of the data and decide the suitable imputation methods for certain columns, then utilizing  `Talend Data Preparation` is used for data profiling and data cleansing, then the Impute Node is used to do imputations on determined columns.
4. **Data Exploration**:  
• Basic exploration Univariate, Bivariate, Multivariate Analysis
• Variable Selection with Decision Tree
• Association Rule.  
• Sequence Analysis.  
• Time Series Clustering.
• Clustering Analysis. (Cluster Node)
• DBSCAN clustering using `KNIME`.
6. **Modify**: Dropping variables using the results from 'Variable Selection with Decision Tree', then data partition was performed follwed by one-hot encoding and standardization.
7. **Modeling** with `SAS Enterprise Miner`:  
• Decision Tree.
• Random Forest.
• Gradient Boosting.
• Neural Network.
• Support Vector Machine 

## Objective:
The main objective is to apply the SEMMA Methodology to carry out in-depth data mining to extract meaningful insights and enhance the dataset's utility.
The objectives of carrying out this project are as follows: 
• To analyze seasonality in hotel bookings to discern peak and off-peak periods.
• To explore relationships between variables in reservation records 
• To segment customer groups that share similar characteristics for marketing strategies.
• To identify key factors influencing booking cancellations.
• To identify clusters of similar time series trends to understand variations in booking patterns over time.
• To identify associations between different website navigation patterns
• To identify the sequence of pages visited that leads to bookings confirmation.
• To build models that predict the likelihood of a booking being canceled for enhancing inventory and pricing strategies.
