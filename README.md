# 🔥 Forest Fire Analysis & Prediction Using CRISP-DM  

## 📌 Project Overview  
This project applies the **CRISP-DM (Cross-Industry Standard Process for Data Mining)** methodology to analyze and predict forest fires using machine learning techniques. The dataset contains meteorological and environmental factors that influence fire occurrence and severity.  

---

## 📊 Dataset Information  
**Source:** Forest Fires dataset url: https://www.kaggle.com/datasets/elikplim/forest-fires-data-set  

### **Features:**  
- **Categorical:** `month`, `day`  
- **Numerical:** `temperature`, `humidity`, `wind speed`, `rainfall`, `FFMC`, `DMC`, `DC`, `ISI`, `burned area (ha)`  
- **Target Variable:** `area` (burned area of the fire)  

---

## 🔄 Project Workflow (CRISP-DM Phases)  

### 1️⃣ Business Understanding  
**Objective:** Understand factors affecting forest fires and predict fire severity.  

**Key Questions:**  
- What environmental factors influence forest fires?  
- Can we predict the burned area using meteorological data?  

### 2️⃣ Data Understanding  
**Performed Exploratory Data Analysis (EDA):**  
✔ Checked for missing values and duplicates.  
✔ Visualized feature distributions using histograms and box plots.  
✔ Identified correlations using a heatmap.  
✔ Found that fires are more frequent in **summer months (June–September).**  

### 3️⃣ Data Preparation  
**Preprocessing steps:**  
✅ Encoded categorical features (`month`, `day`).  
✅ Scaled numerical values for consistent model performance.  
✅ Identified and handled outliers in the `area` column.  
✅ Checked and removed any duplicate records.  

### 4️⃣ Modeling  
Applied different **regression models** to predict fire severity:  
- **Linear Regression**  
- **Random Forest Regressor**  
- **Support Vector Regressor (SVR)**  

**Model Performance Comparison:**  
- **Root Mean Square Error (RMSE)**  
- **Mean Absolute Error (MAE)**  
- **R² Score**  

### 5️⃣ Evaluation  
🚀 The **Random Forest model** performed the best with a **lower RMSE** and a **higher R² score.**  
📌 **Key Factors Affecting Fire Spread:**  
✔ **Temperature**, **humidity**, and **wind speed** significantly impact fire spread.  
 
---

## 🔑 Key Insights  

### 🔥 1. Fire Occurrence & Severity  
- Most fires **burn small areas**, but **a few extreme cases** exist.  
- Fires are **more frequent in summer months (June–September).**  

### 🌍 2. Environmental Factors Affecting Fires  
- **Higher temperatures** increase fire risk by **drying vegetation.**  
- **Humidity & rainfall** reduce fire spread, but rainfall is usually **low.**  
- **Wind** can spread fires faster, though its effect on **fire size is moderate.**  

### 📊 3. Data Preparation Needs  
- `month` and `day` **need encoding** for modeling.  
- Data contains **outliers** that may require handling.  

---

## 🎨 Visualization Techniques Used  
📌 **Histograms:** Show the distribution of numerical features.  
📌 **Box plots:** Identify outliers.  
📌 **Correlation Matrix (Heatmap):** Observe relationships between variables.  
📌 **Scatter plots:** Visualize trends in fire occurrence.  

---

## ⚙️ Installation & Requirements  
**Python 3.x**  

### Required Libraries:  
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
## 👥 Contributors
STEPHANIE MATHENGE

TERRY SAMARA

STACY MUHIA

JOANNA FURAHA

MARGARET WANGARI

