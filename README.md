Hello! 👋
My name is Maria Clara Brito, and I'm a Data Science student.

#Skills

**Programming and Database:**
  <img width=50,height=50 src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" />
          

**Data Science:**

**Data Visualization:**





Here are some of my projects:

1. Airflow DAG with MongoDB and Data Visualization
For my Architecture and NoSQL class, we were tasked with creating an Airflow DAG that fetches a CSV file and loads it into a database. I chose MongoDB for the database, running inside a Docker container. Additionally, the CSV data was visualized using Power BI or ELK.

📁 You can check out the files and full solution [here](https://github.com/MARIACLARACFBRITO/airflow_docker).

2. Predicting Power Outages Using Weather Data
During my first year at FIAP, we were presented with a challenge by a partner company, Mindsight, to help energy providers like Enel predict power outages caused by weather conditions in São Paulo. Our solution was to develop a simple machine learning model to analyze weather data extracted from an API via a DAG (Airflow) running in a Docker container, combined with open data on energy outages.

📁 Take a look at the final version of our solution .

Predicting Churn
Business Problem
In a Machine Learning course titled "Classificação: aprendendo a classificar dados com Machine Learning," the goal was to develop a model to predict customer churn for a fictitious company. This project focused on creating a classification model to identify customers at higher risk of canceling their services, providing actionable insights for targeted retention strategies.

Solution
To address the problem, we started with an Exploratory Data Analysis (EDA) to gain insights into customer attributes and uncover potential churn patterns.

The following models were evaluated to determine the best predictive approach:

Dummy Classifier: Used as a baseline with an accuracy of 79.64%.
Decision Tree Classifier: Selected for its ability to capture complex decision patterns, achieving an accuracy of 84.64%.
K-Nearest Neighbors (KNN): Implemented to leverage customer similarity, with an accuracy of 81.72%.
After testing, the Decision Tree model proved to be the best model for predicting churn, with the highest accuracy.

Business Result
By deploying the Decision Tree model, the fictitious company could predict customer churn with an accuracy of 84.64%, allowing for more efficient resource allocation towards customer retention. This approach potentially:

Reduces churn by accurately identifying high-risk customers.
Optimizes the retention budget by focusing actions on customers most likely to cancel.

Project:[Predicting Churn-Using ML](https://github.com/MARIACLARACFBRITO/)
