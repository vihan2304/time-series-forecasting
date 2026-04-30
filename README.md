# 📊 Time Series Forecasting using Multi-Step Strategies

## 📌 Overview
This project explores different multi-step forecasting strategies to predict future values of time series data.  
The goal is to compare how different approaches behave in practice and identify which performs best for the given dataset.

---

## 🎯 Problem Statement
In real-world applications such as demand forecasting, sales prediction, and financial analysis, predicting multiple future time steps is crucial.  
This project aims to evaluate different forecasting strategies and analyze their effectiveness.

---

## 🚀 Methods Implemented

### 1. Recursive Strategy
- Uses previous predictions as input for future steps  
- Simple and efficient  
- Can accumulate error over longer horizons  

### 2. Direct Strategy
- Builds separate models for each future step  
- Reduces error propagation  
- Requires more computation  

### 3. MIMO (Multi-Input Multi-Output using KNN)
- Predicts multiple future values at once  
- Captures dependencies between outputs  
- Performance depends on data quality and model choice  

---

## 📊 Evaluation Metric
- **RMSE (Root Mean Square Error)**  
- Measures the difference between predicted and actual values  
- Lower RMSE indicates better performance  

---

## 📈 Results & Insights
- Recursive strategy achieved the **lowest RMSE** in this experiment  
- Direct strategy provided stable predictions but with slightly higher error  
- MIMO approach performed worse, likely due to dataset size and limitations of the KNN model  

👉 **Conclusion:**  
For this dataset, the **Recursive strategy performed best** for multi-step forecasting.  
However, it is important to note that Recursive methods may accumulate error over longer prediction horizons, and results can vary depending on the dataset and model used.

---

## 📉 Sample Output
Predicted values were compared with actual values to evaluate model performance.  
Recursive predictions showed closer alignment with actual data in this experiment.

---

## 🧠 Key Learnings
- Different multi-step forecasting strategies behave differently in practice  
- Recursive models can outperform others in certain conditions  
- Model performance depends heavily on data and algorithm choice  
- Understanding trade-offs is more important than blindly applying methods  

---

## 🛠️ Tech Stack
- Python  
- K-Nearest Neighbors (KNN)  
- Basic data structures and logic implementation  

---

## ▶️ How to Run
1. Clone the repository  
2. Open the notebook or Python file  
3. Run all cells to generate predictions and evaluate results  

---

## 🔗 Future Improvements
- Add visualization (Actual vs Predicted graphs)  
- Experiment with advanced models like ARIMA and LSTM  
- Perform hyperparameter tuning for improved accuracy  

---

## 💡 Project Highlights
- Implemented multiple forecasting strategies from scratch  
- Compared models using a real evaluation metric (RMSE)  
- Focused on understanding core concepts instead of relying on libraries  
- Analyzed results critically instead of assuming theoretical outcomes  

---
## 📊 Visualization

### Actual vs Predicted Values (Comparison of Recursive, Direct, and MIMO)

![Forecast Comparison](https://raw.githubusercontent.com/vihan2304/time-series-forecasting/main/image.png)

This project demonstrates how practical results can differ from theoretical expectations, highlighting the importance of experimentation in data science.
