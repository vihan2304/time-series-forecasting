# 📊 Time Series Forecasting using Multi-Step Strategies

## 📌 Project Overview
This project focuses on forecasting future values of time series data using different multi-step forecasting strategies. The goal is to understand how different approaches perform when predicting multiple future steps.

---

## 🚀 Methods Used
- **Recursive Strategy** – Uses previous predictions as input for future steps  
- **Direct Strategy** – Builds separate models for each future step  
- **MIMO (Multi-Input Multi-Output using KNN)** – Predicts multiple steps at once  

---

## 📊 Evaluation Metric
- **RMSE (Root Mean Square Error)** used to measure prediction accuracy  

---

## 📈 Results
- MIMO showed better performance compared to other strategies in multi-step forecasting  
- Recursive method accumulated errors over time  
- Direct method improved stability but required multiple models  

---

## 🧠 Key Learnings
- Multi-step forecasting strategies behave differently depending on approach  
- MIMO can capture dependencies between future values more effectively  
- Choosing the right strategy is important for real-world forecasting tasks  

---

## 🔗 Future Improvements
- Add visualization (Actual vs Predicted graphs)  
- Use advanced models like ARIMA or LSTM  
- Optimize model performance  

---

## 🛠️ Tech Stack
- Python  
- Basic Machine Learning (KNN)  
- No external forecasting libraries used  

