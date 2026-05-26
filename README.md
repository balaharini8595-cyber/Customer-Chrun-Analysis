ReadMe Content:

 Customer Churn Analysis System

 Project Overview

Customer churn analysis is an important process used by businesses to identify customers who are likely to stop using a product or service.
This project focuses on generating **synthetic customer data** using the **Faker library** and performing **Exploratory Data Analysis (EDA)** to identify churn patterns and customer behavior.

The project helps businesses:

* Understand customer behavior
* Detect churn patterns
* Identify high-risk customers
* Improve customer retention strategies

 Problem Statement

Customer churn is one of the biggest challenges faced by businesses such as banks, telecom companies, and subscription services.

When customers leave:

* Revenue decreases
* Customer acquisition costs increase
* Business growth is affected

Real-world customer datasets are often unavailable due to privacy concerns. Therefore, this project generates synthetic customer data and performs analysis to understand factors influencing churn.

 Dataset Information

This project generates **100,000 synthetic customer records** using the Faker library.

 Dataset Columns

| Column Name     | Description                |
| --------------- | -------------------------- |
| Customer_ID     | Unique customer identifier |
| Age             | Customer age (18–70)       |
| Gender          | Male / Female              |
| Tenure          | Years with company         |
| Balance         | Account balance            |
| CreditScore     | Customer credit score      |
| EstimatedSalary | Annual income              |
| NumOfProducts   | Number of products used    |
| IsActiveMember  | Active or inactive member  |
| Churn           | 0 = No Churn, 1 = Churn    |

 Objectives

The main objective of this project is to perform **Exploratory Data Analysis (EDA)** on synthetic customer data.

 Key Objectives:

* Generate realistic synthetic data
* Perform data cleaning and preprocessing
* Analyze churn behavior
* Identify churn factors
* Visualize customer patterns
* Generate business insights

 Technologies Used

* Python 
* Pandas
* NumPy
* Faker
* Matplotlib
* Seaborn
* Google Colab

 Project Workflow

 1. Data Generation

* Generate synthetic customer records using Faker
* Simulate real-world banking/customer scenarios

 2. Data Preprocessing

* Check missing values
* Verify data types
* Remove inconsistencies
* Encode categorical variables

 3. Descriptive Statistics

* Mean
* Median
* Standard Deviation
* Data distribution analysis

 4. Churn Analysis

* Compare churn vs non-churn customers
* Identify high churn segments
* Analyze active and inactive members

 5. Relationship Analysis

* Balance vs Churn
* Credit Score vs Churn
* Tenure vs Churn
* Gender vs Churn

 6. Data Visualization

* Count plots
* Histograms
* Box plots
* Scatter plots
* Heatmaps
* Pie charts

Visualizations Included

* Churn Count Plot
* Gender vs Churn
* Age Distribution
* Balance vs Churn
* Credit Score vs Balance
* Correlation Heatmap
* Churn Percentage Pie Chart

 Key Insights

* Inactive customers show higher churn probability
* Low balance and low credit score customers are more likely to churn
* Customer activity significantly affects retention
* Certain age groups have higher churn patterns

 Future Improvements

* Apply Machine Learning models for churn prediction
* Build interactive dashboards using Power BI or Tableau
* Deploy the model as a web application
* Improve churn prediction accuracy using advanced algorithms

Output overview:
<img width="709" height="570" alt="image" src="https://github.com/user-attachments/assets/7aee5171-906e-4e16-9617-ac455eca2925" />
<img width="708" height="542" alt="image" src="https://github.com/user-attachments/assets/e8abb725-dcb2-4ad9-a775-638045a17411" />
<img width="682" height="510" alt="image" src="https://github.com/user-attachments/assets/545fd725-9524-484e-94c3-ffeb8650f0f4" />
<img width="733" height="563" alt="image" src="https://github.com/user-attachments/assets/2320ffea-f79a-4195-aa8b-343116488f89" />
<img width="734" height="564" alt="image" src="https://github.com/user-attachments/assets/70017637-215b-41ec-954f-14816487e1c7" />
<img width="1103" height="762" alt="image" src="https://github.com/user-attachments/assets/be21cafb-5a5d-4b32-a70a-57b2bfcd2453" />
<img width="489" height="509" alt="image" src="https://github.com/user-attachments/assets/ab7c4cec-7cf1-4b27-84e5-d5df769e9522" />



 Conclusion

This project demonstrates how synthetic customer data can be generated and analyzed to understand customer churn behavior.
The insights obtained from EDA help businesses improve customer retention and make better strategic decisions.
