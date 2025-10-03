# SuperKart Model Deployment

## Overview  
This project focuses on building, training, and deploying a sales forecasting solution for **SuperKart**, a retail chain operating supermarkets across multiple cities. The goal is to predict future sales revenue for different products and stores, enabling better inventory planning, procurement decisions, and regional sales strategies.

## Objective  
The main objective was to develop a machine learning model that accurately forecasts product-level sales and deploy it as a production-ready application. The solution helps business teams operationalize insights, reduce forecasting risks, and improve supply chain efficiency.

## Dataset  
- **Source:** Provided as part of the project coursework  
- **Key Features:**  
  - Product details (weight, category, MRP, sugar content)  
  - Store attributes (size, location type, establishment year)  
  - Historical sales performance  
- **Target:** Total revenue generated per product-store combination

## Workflow  
1. **Data Preprocessing & EDA** – Cleaned and analyzed historical sales data, engineered new features, and explored sales trends.  
2. **Model Development** – Built multiple regression models and optimized them with hyperparameter tuning.  
3. **Model Selection & Serialization** – Compared model performance, selected the best model, and serialized it for deployment.  
4. **Deployment** – Created a Flask API backend and Streamlit frontend, containerized with Docker, and deployed on Hugging Face Spaces.

## Results & Key Insights  
- Built a robust forecasting solution enabling better inventory and sales planning.  
- Integrated a complete MLOps workflow, from data processing to API and web deployment.  
- Demonstrated how predictive analytics can drive strategic retail decisions.

## Tech Stack  
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Flask, Streamlit  
- **Tools:** Docker, Hugging Face Spaces, Jupyter Notebook / Google Colab  

## Author  
**Sandesh S. Badwaik**  
- [LinkedIn](https://www.linkedin.com/in/sbadwaik/)
