# 🛵 Food Delivery Route Efficiency & Delivery Time Prediction

This project analyzes food delivery operations using exploratory data analysis (EDA) and machine learning to understand the factors that influence delivery time. It also includes an interactive Gradio web app that predicts delivery time based on user inputs.

## 📌 Project Overview

The goal of this project is to identify key contributors to delivery delays and build predictive models that help optimize last-mile delivery performance. The dataset includes variables such as:

- Distance (km)

- Traffic level

- Weather conditions

- Route length (km)

- Delivery mode

- Restaurant and customer zones

## 🔍 Key Analyses
1. Route Inefficiency

Calculated the inefficiency ratio (route_length_km / distance_km) to measure path effectiveness across delivery modes and zones.

2. Traffic & Weather Impact

Analyzed how different traffic levels and weather conditions influence both speed and delivery duration.

3. Zone-Based Insights

Evaluated average distance, delivery time, and route length between restaurant and customer zones.

4. Exploratory Data Analysis (EDA)

Generated scatterplots and a correlation heatmap to understand relationships among variables.

## 🤖 Machine Learning Models Used

The following regression models were trained and tested:

- AdaBoost Regressor

- Gradient Boosting Regressor

- Random Forest Regressor

- Decision Tree Regressor

- XGBoost Regressor

Result: Gradient Boosting achieved the highest performance with a very low MAE and a high R² score.

🧪 Gradio App

A user-friendly Gradio interface was built to provide real-time delivery time predictions based on:

- Distance

- Traffic level

- Route length

- Weather

- Delivery mode

- Restaurant & customer zones

- Inefficiency

- Speed

## 📁 Technologies Used

- Python

- Pandas, NumPy

- Matplotlib, Seaborn

- Scikit-learn

- XGBoost

- Gradio

## 🚀 Outputs

- Insights on delivery inefficiency and performance

- Machine learning models for delivery time prediction

- Interactive prediction web app

## Citations

https://scikit-learn.org/stable/index.html

https://www.geeksforgeeks.org/artificial-intelligence/python-creating-user-interfaces-for-ai-models-using-gradio/

ChatGPT
