🔥 Seoul Bike Rental Analysis & Prediction Using CRISP-DM 

📌 Project Overview 

This project applies the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology to analyze and predict bike rentals in Seoul using machine learning techniques. The dataset contains temporal and environmental factors that influence bike renting. 

 

📊 Dataset Information 

Source: Seoul bike rental data set url: [https://www.kaggle.com/datasets/joebeachcapital/seoul-bike-sharing/data]  

🔄 Project Workflow (CRISP-DM Phases) 

1️⃣ Business Understanding 

* **Objective:** To accurately predict the number of bikes rented on an hourly basis in Seoul, South Korea. * **Business Context:** Bike sharing systems are increasingly popular in urban areas. Accurate demand forecasting can help optimize bike availability, improve customer satisfaction, and enhance operational efficiency. * **Success Criteria:** The project will be considered successful if the developed model achieves a low Root Mean Squared Error (RMSE) and a high R-squared score, indicating accurate predictions of bike rental counts. 

 

 

2️⃣ Data Understanding 

Performed Exploratory Data Analysis (EDA): 
* **Dataset Source:** The Seoul Bike Sharing Demand dataset, available on Kaggle: [https://www.kaggle.com/datasets/joebeachcapital/seoul-bike-sharing/data](https://www.kaggle.com/datasets/joebeachcapital/seoul-bike-sharing/data). * **Dataset Description:** The dataset contains hourly bike rental counts from December 2017 to November 2018 in Seoul, along with corresponding weather and time-related information. * **Key Features:** * **Date:** Date of the rental. * **Rented Bike Count:** The number of rented bikes (target variable). * **Hour:** The hour of the day (0-23). * **Temperature(°C):** Temperature in Celsius. * **Humidity(%):** Humidity percentage. * **Wind speed (m/s):** Wind speed in meters per second. * **Visibility (10m):** Visibility in 10-meter units. * **Dew point temperature(°C):** Dew point temperature in Celsius. * **Solar Radiation (MJ/m2):** Solar radiation in Mega Joules per square meter. * **Rainfall(mm):** Rainfall amount in millimeters. * **Snowfall (cm):** Snowfall amount in centimeters. * **Seasons:** Season of the year (Winter, Spring, Summer, Autumn). * **Holiday:** Holiday status (No Holiday, Holiday). * **Functioning Day:** Functioning day status (Yes, No). * **Initial Data Exploration:** [**Describe initial data exploration, such as summary statistics, data distributions, and initial observations.**] 

3️⃣ Data Preparation 

Preprocessing steps: 
✅ Encoded categorical features. 
✅ Scaled numerical values for consistent model performance. 
✅ Identified and handled outliers. 
✅ Checked and removed any duplicate records. 

4️⃣ Modeling 

Applied different regression models to predict the number of bikes rented: 

Linear Regression 

Random Forest Regressor 

Model Performance Comparison: 

Root Mean Square Error (RMSE) 

Mean Absolute Error (MAE) 

R² Score 

5️⃣ Evaluation 

🚀 The XGBoost performed the best with a lower RMSE and a higher R² score. 
📌 Key Factors Affecting Fire Spread: 
✔ Temperature, humidity, and wind speed significantly impact fire spread. 

 

🎨 Visualization Techniques Used 

📌 Histograms: Show the distribution of numerical features. 
📌 Box plots: Identify outliers. 
📌 Correlation Matrix (Heatmap): Observe relationships between variables. 
 

 

⚙️ Installation & Requirements 

Python 3.x 

Required Libraries: 

pip install pandas numpy matplotlib seaborn scikit-learn 

👥 Contributors 

STEPHANIE MATHENGE 

TERRY SAMARA 

STACY MUHIA 

JOANNA FURAHA 

MARGARET WANGARI 

 
