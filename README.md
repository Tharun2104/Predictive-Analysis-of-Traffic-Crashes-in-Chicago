# Predictive Modeling of Traffic Accidents in Chicago: Crash Classification and Damage Assessment

This project aims to analyze traffic accidents in Chicago to classify crash types, estimate damage severity, and identify risk factors associated with severe collisions. By integrating advanced data analytics, machine learning models, distributed computing with Apache Spark, and an interactive web platform, this study provides valuable insights to enhance urban traffic safety management.

dataset source - https://catalog.data.gov/dataset/traffic-crashes-crashes


## Phase 1: Data Preprocessing and Exploratory Analysis
A comprehensive data preprocessing pipeline was applied to traffic crash records from June to December 2023. Key steps included:
- Addressing missing and inconsistent data
- Encoding categorical variables
- Standardizing feature formats

Exploratory Data Analysis (EDA) was conducted to uncover underlying trends and relationships, forming the basis for predictive modeling.

## Phase 2: Machine Learning for Crash Prediction
Several machine learning models were trained to predict crash types and analyze contributing factors, including:
- **Logistic Regression**
- **Random Forest**
- **Support Vector Machine (SVM)**
- **XGBoost**

Among these, **XGBoost** outperformed others, achieving an **accuracy of 89.3%** and an **AUC score of 0.95**, making it the most suitable model for real-world deployment.

## Phase 3: Scalable Data Processing with PySpark
To handle large-scale datasets efficiently, **PySpark** was utilized for data preprocessing and model training. This approach enabled:
- Processing over **1.5 million records** efficiently
- Enhanced scalability and fault tolerance
- Faster execution of machine learning workflows

PySpark's distributed processing capabilities significantly improved the efficiency and performance of the predictive analysis.

## Interactive Web Platform
A **web-based interface** was developed to present findings in an accessible manner. The platform allows users to:
- Upload crash datasets for real-time analysis
- Visualize patterns and trends through interactive dashboards
- Generate crash type and severity predictions
- Explore key risk factors influencing accidents

## Conclusion
This project highlights the effectiveness of **machine learning, big data processing with Apache Spark, and interactive web applications** in addressing urban traffic challenges. By leveraging **XGBoost** for predictive accuracy, **PySpark** for scalability, and a **web interface** for accessibility, this framework supports **data-driven decision-making** for road safety improvements, optimized resource allocation, and enhanced public safety strategies.
