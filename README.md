

# 🚴 Bicycle Crash Risk & Infrastructure Safety Analysis

This project analyzes bicycle crash risk using machine learning and spatial data, with a focus on understanding how infrastructure and road characteristics influence safety. It also simulates infrastructure improvements to evaluate their potential impact on reducing crash risk.


## 📌 Overview

Urban cycling safety is a critical issue in modern cities. This project builds a data-driven framework to:

* Predict bicycle crash risk at the road-segment level
* Identify high-risk areas
* Understand key contributing factors
* Simulate infrastructure interventions (e.g., bike lanes)

The approach combines geospatial data, feature engineering, and machine learning models to provide actionable insights for safer urban planning.


## 🧠 Key Features

* End-to-end pipeline from raw data to model evaluation
* Feature engineering for infrastructure, road, and spatial attributes
* Risk prediction using machine learning models (e.g., XGBoost)
* Scenario simulation for infrastructure improvements
* Visualization of risk distribution across road segments


## ⚙️ Methodology

### 1. Data Preparation

* Cleaning and filtering raw geospatial and crash data
* Handling missing values and inconsistencies
* Mapping crashes to road segments

### 2. Feature Engineering

Features are grouped into three main categories:

* **Infrastructure**

  * Bicycle lanes
  * Road type and configuration
  * Presence of cycling network

* **Road Characteristics**

  * Road length
  * Number of lanes
  * One-way / two-way

* **Spatial & Contextual**

  * Distance to intersections
  * Traffic-related attributes


### 3. Modeling

* Machine learning models trained to predict crash risk
* Hyperparameter tuning (e.g., Optuna with XGBoost)
* Evaluation using appropriate metrics (e.g., precision-focused analysis)


### 4. Scenario Simulation

* Simulated infrastructure improvements on high-risk segments
* Example: Adding bike lanes to top-risk roads
* Measured reduction in predicted crash probability


## 📊 Key Results

* High-risk segments can be effectively identified using ML models
* Infrastructure features (especially bike lanes) significantly impact safety
* Simulated interventions show measurable reductions in predicted crash risk


## 🛠️ Tech Stack

* Python
* Pandas / NumPy
* Scikit-learn
* XGBoost
* Optuna
* Geospatial libraries (e.g., GeoPandas, Shapely)
* Plotly / Matplotlib


## 📈 Future Work

* Incorporate real-time traffic and weather data
* Extend to multiple cities for generalization
* Integrate deep learning or graph-based models
* Build an interactive dashboard for planners
