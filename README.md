# 🚗 Car Price Prediction
📌 Overview
This project aims to analyze and model car pricing data to uncover key factors that influence car prices. Using exploratory data analysis and machine learning, the goal is to build a predictive model that estimates the price of a car based on its features.

🗃️ Dataset
Dataset Name: cardekho.csv
Source: Assumed to be sourced from Cardekho or a similar platform

🔑 Features:
name – Car model name

year – Manufacturing year

selling_price – Target variable (price of the car)

km_driven – Distance the car has traveled

fuel – Fuel type (Petrol, Diesel, etc.)

seller_type – Type of seller (Individual, Dealer)

transmission – Manual/Automatic

owner – Ownership status

mileage, engine, max_power – Performance indicators

seats – Seating capacity

🔍 Project Stages
Data Loading & Cleaning

Handle missing values

Convert appropriate data types

Feature extraction from strings (e.g., numeric from engine, mileage)

Exploratory Data Analysis (EDA)

Understand distribution of features

Analyze price trends across car types, brands, and features

Feature Engineering

Encode categorical variables

Create new relevant features

Modeling

Regression models to predict selling_price

Evaluate models using metrics like MAE, RMSE, and R²

📊 Tools & Libraries Used
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn (Regression Models)

🎯 Goals
Identify top features that influence car resale value

Predict price for unseen car listings

Help users make informed decisions in used car markets
