## Weather Forecasting 
**Duration:** Jan 2023 – May 2023  
**Tools & Tech:** Python, Apache Airflow, Streamlit, SQL, Google Cloud Storage, Tableau, Databricks  

### Overview  
This project aimed to develop a robust and scalable weather prediction system using historical weather data from Boulder, CO (2021–2023). By combining ETL pipelines, machine learning models, and interactive visualizations, the project provides users with an intuitive tool for forecasting weather patterns and analyzing climatic trends.

### Key Contributions  
- **ETL Pipeline Development:** 
  - Built a fully automated data pipeline using **Apache Airflow** to extract daily weather data from Visual Crossing.
  - Used SQL queries to filter and transform the data.
  - Stored processed data in **Google Cloud Storage** for centralized access and further analysis.

- **Machine Learning & Model Evaluation:**  
  - Explored multiple models including **Random Forest**, **Support Vector Machines (SVM)**, and **Gradient Boosting** to predict weather conditions like temperature and humidity.
  - Achieved **85% prediction accuracy** with Gradient Boosting, identified through hyperparameter tuning on **Databricks**.

- **Interactive Streamlit Application:**  
  - Created a web app using **Streamlit** that allows users to input specific parameters (e.g., humidity, temperature, wind speed).
  - The app returns weather predictions and visual analytics in real time.

- **Data Visualization with Tableau:**  
  - Built dynamic dashboards to display:
    - Temperature trends over time
    - Humidity and precipitation variations
    - Wind speeds and seasonal patterns
    - Anomalous weather events
