
# 🚔 FBI Crime Investigation - Time Series Forecasting

## 📌 Overview

This project focuses on analyzing and forecasting crime incidents using historical FBI crime data. By leveraging time series analysis and machine learning techniques, the goal is to predict future crime occurrences and provide actionable insights for law enforcement agencies.

The project demonstrates an end-to-end data science workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, evaluation, and deployment readiness.

---

## 🎯 Objective

* Analyze historical crime data to identify patterns and trends
* Forecast future crime incidents using time series techniques
* Enable data-driven decision-making for crime prevention
* Optimize resource allocation for law enforcement agencies

---

## 📂 Dataset Description

The dataset contains detailed information about crime incidents, including:

* **Crime Type (TYPE)** – Category of crime
* **Location Data** – Latitude, Longitude, Neighborhood
* **Time Features** – Year, Month, Day, Hour, Minute
* **Incident_Counts** – Number of crime incidents (Target Variable)

---

## 🧠 Key Steps Performed

### 🔹 1. Data Preprocessing

* Handled missing values and duplicates
* Converted date columns into datetime format
* Sorted data chronologically for time series analysis

### 🔹 2. Feature Engineering

* Created lag features (lag_1, lag_2, lag_3)
* Generated rolling mean features
* Extracted time-based features (Month, Day, Weekend, etc.)

### 🔹 3. Exploratory Data Analysis (EDA)

* Performed Univariate, Bivariate, and Multivariate analysis
* Created 15+ visualizations
* Identified:

  * Peak crime hours
  * Seasonal patterns
  * High-risk neighborhoods

### 🔹 4. Model Building

Implemented multiple models:

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor

### 🔹 5. Model Evaluation

Used key metrics:

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score

---

## 🏆 Best Model

**XGBoost Regressor** achieved the best performance due to its ability to capture complex patterns in time series data.

---

## 📊 Key Insights

* Crime incidents show strong **seasonal trends**
* Certain neighborhoods contribute disproportionately to crime
* Night hours show increased crime activity
* Lag features significantly improve prediction accuracy

---

## 🚀 Business Impact

* Helps law enforcement predict crime spikes
* Enables optimized patrol scheduling
* Supports proactive crime prevention strategies
* Assists in urban safety planning

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn, XGBoost
* **Model Saving:** Joblib

---

## 📦 Project Structure

```
├── data/
│   ├── Train.xlsx
│   ├── Test.csv
├── notebooks/
│   └── FBI_Crime_Forecasting.ipynb
├── models/
│   └── crime_forecast_model.pkl
├── README.md
```

---

## 🔮 Future Improvements

* Incorporate real-time data streams
* Add weather and socio-economic features
* Use advanced models like ARIMA, LSTM
* Deploy as a web application

---

## 📌 How to Run the Project

```bash
# Clone the repository
git clone https://github.com/your-username/fbi-crime-forecasting.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

## 📬 Contact

If you found this project useful, feel free to connect with me on LinkedIn or GitHub.

---

⭐ If you like this project, don’t forget to star the repository!
