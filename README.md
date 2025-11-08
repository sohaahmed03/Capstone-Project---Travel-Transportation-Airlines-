GE372 – Big Data Analytics Capstone Project
✈️ Travel & Transportation Industry (Airlines)

Topic: Big Data Analytics in Aviation Industry

Student: Soha Ahmed
Roll No: 24MBMA03
Program: MBA (General), 2nd Year

🎯 Project Overview

This capstone project demonstrates the application of Big Data Analytics in the aviation industry using Databricks and PySpark.
The objective is to analyze large-scale airline data to address challenges in operations, customer experience, and pricing optimization.

By leveraging distributed data processing and Spark ML pipelines, five distinct use cases were implemented to showcase scalability, complexity handling, and real-time analytical power of Big Data tools.

🧩 Five Big Data Use Cases

1️⃣ Flight Delay Prediction:
Predicted and analyzed delay patterns using PySpark ML (Logistic Regression) to improve scheduling efficiency.

2️⃣ Airline Customer Segmentation:
Identified satisfaction drivers and predicted passenger satisfaction using Spark ML classification models.

3️⃣ Route and Schedule Optimization:
Used graph analytics (NetworkX with Spark) to identify highly connected airports and optimize route networks.

4️⃣ Sentiment Analysis of Passenger Feedback:
Applied Spark MLlib NLP (TF-IDF and Logistic Regression) on airline tweets to analyze customer perception.

5️⃣ Dynamic Pricing Analysis:
Developed a Spark-based Linear Regression model to predict ticket prices using multiple flight-related features.

🧱 Technology Stack

This project was implemented using:

🖥️ Big Data Platform: Databricks Community Edition

⚙️ Distributed Processing: Apache Spark (PySpark)

🤖 Machine Learning: Spark MLlib (Logistic Regression, Linear Regression, K-Means)

🌐 Graph Analytics: NetworkX integrated with Spark

📊 Visualization: Plotly Dash, Matplotlib, and Databricks Visualizations

💻 Languages: Python, SQL, and PySpark

💾 Storage: DBFS (Databricks FileStore) and Spark Tables

🗂️ Version Control: GitHub

🧾 Datasets Used

All datasets were obtained from Kaggle and other public repositories.
The project used five datasets covering various aspects of airline operations:

✈️ Airlines Delay Data: U.S. flight on-time performance dataset

😊 Airline Passenger Satisfaction: Passenger survey results and service ratings

🌍 OpenFlights Route Database: Global airline route and connectivity information

💬 Twitter US Airline Sentiment: 14,000+ labeled tweets analyzing airline service perception

💰 Flight Price Prediction Data: Flight ticket prices, travel class, and route attributes

📁 The datasets are stored in the datasets/ folder.

⚙️ Methodology

Data Ingestion: Imported datasets into Databricks workspace and Spark environment.

Data Cleaning: Used PySpark transformations to handle nulls, fix data types, and standardize schemas.

Exploratory Data Analysis (EDA): Conducted SQL and visual analysis within Databricks to uncover trends.

Feature Engineering: Encoded categorical features, created numeric features, and scaled data for ML pipelines.

Model Building: Developed Logistic Regression, Linear Regression, and K-Means clustering models using Spark MLlib.

Evaluation: Measured ROC-AUC, Accuracy, RMSE, and R² for model performance.

Visualization & Reporting: Combined all results into an interactive dashboard for unified insights.

📊 Results & Insights

✈️ Flight Delay Prediction: Identified airlines with high delay probabilities (ROC-AUC = 0.82).

😊 Customer Segmentation: Online boarding, seat comfort, and travel type were top satisfaction drivers.

🌍 Route Optimization: Airports like LHR, ATL, and DXB emerged as major global connection hubs.

💬 Sentiment Analysis: Over 60% of negative tweets were about delays and poor service quality.

💰 Price Prediction: Business class fares were nearly 3× higher than economy (R² = 0.79).

🖥️ Visualization Dashboard

All five analyses were integrated into a single Aviation Analytics Dashboard.
The dashboard provides:

📈 Individual visualizations for each use case

💡 Insights and interpretations placed below each chart

🧭 An executive summary highlighting key business recommendations


🗂️ Project Structure
Capstone-Project-Aviation/
│
├── README.md
├── datasets/
│   ├── 1_Airlines_Delay.csv
│   ├── 2_Passenger_Satisfaction.csv
│   ├── 3_Flight_Route_Database.csv
│   ├── 4_Twitter_US_Airline_Sentiment.csv
│   └── 5_Flight_Price_Prediction.csv
│
├── notebooks/
│   ├── Case1_FlightDelay.ipynb
│   ├── Case2_Satisfaction.ipynb
│   ├── Case3_RouteOptimization.ipynb
│   ├── Case4_SentimentAnalysis.ipynb
│   ├── Case5_PricingAnalysis.ipynb
│   └── Capstone_All_Cases.dbc
│
├── dashboard/
│   └── Aviation_Dashboard.py
│
└── requirements.txt

Conclusion

This Big Data Capstone Project integrates PySpark, Databricks, and Spark MLlib to address real-world challenges in the airline industry.
Through distributed data processing, predictive modeling, and interactive visualization, the project demonstrates how Big Data Analytics can transform raw aviation data into actionable business insights — improving efficiency, decision-making, and customer satisfaction.
