# 🚲 Yulu Bike Demand Analysis Using Hypothesis Testing

## 📌 Project Overview
Yulu is one of India’s leading micro-mobility service providers offering shared electric bikes for sustainable and convenient last-mile connectivity. Recently, Yulu experienced a decline in revenue and aims to understand the key factors influencing bike rental demand.

This project uses Exploratory Data Analysis (EDA) and Statistical Hypothesis Testing to identify patterns and factors affecting rental demand.

---

## 🎯 Business Objective
The primary objectives of this project are:

- Identify variables significantly influencing bike rental demand
- Analyze demand differences between weekdays and weekends
- Evaluate the impact of weather conditions on rental demand
- Study seasonal variations affecting bike usage
- Provide data-driven business recommendations

---

## 📊 Dataset Information

The dataset contains historical bike rental records with the following features:

- **datetime** – Timestamp of rental data  
- **season** – Season category  
- **holiday** – Whether the day is a holiday  
- **workingday** – Whether the day is a working day  
- **weather** – Weather condition category  
- **temp** – Temperature  
- **atemp** – Feels-like temperature  
- **humidity** – Humidity level  
- **windspeed** – Wind speed  
- **casual** – Number of casual users  
- **registered** – Number of registered users  
- **count** – Total number of bike rentals  

---

## 🛠 Tools & Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy  
- Statistical Hypothesis Testing  

---

## 🔍 Analysis Performed

### 1. Exploratory Data Analysis
- Dataset structure and statistical summary
- Missing value handling
- Duplicate record removal
- Distribution analysis of numerical and categorical variables
- Outlier detection and treatment
- Correlation analysis

---

### 2. Hypothesis Testing

| Business Question | Statistical Test Used |
|-------------------|----------------------|
| Difference in demand between weekdays and weekends | Independent T-Test |
| Demand variation across weather conditions | One-way ANOVA |
| Demand variation across seasons | One-way ANOVA |
| Relationship between weather and season | Chi-Square Test |

---

## 📈 Key Insights

- Bike rental demand significantly varies between working days and non-working days.
- Weather conditions strongly influence customer rental behavior.
- Seasonal variations impact overall rental demand.
- Weather distribution patterns differ across seasons.

---

## 💡 Business Recommendations

- Increase bike availability during peak working days.
- Optimize fleet allocation based on seasonal demand trends.
- Use weather forecasts to improve operational planning.
- Implement targeted marketing strategies during low-demand periods.

---

## 👩‍💻 Author
Priyanka
Aspiring Data Analyst


