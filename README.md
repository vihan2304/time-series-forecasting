# 📊 Time Series Forecasting Model Comparison

## 🚀 Project Overview

This project focuses on comparing different **time series forecasting strategies** to predict **LME Cash Settlement prices** over a 28-day horizon.

The goal is to evaluate model performance using **MAPE (Mean Absolute Percentage Error)** and identify the most accurate approach.

---

## 🧠 Models Implemented

* 🔁 **Recursive Strategy**
* 📦 **Direct Strategy**
* 🔗 **Hybrid Strategy (Regressor Chain)**
* 🎯 **MIMO Strategy (Multi-Input Multi-Output)**

---

## ⚙️ Techniques Used

* Lag-based feature engineering
* Multivariate time series modeling
* Hyperparameter tuning (GridSearchCV)
* TimeSeriesSplit cross-validation
* Post-processing:

  * Bias correction
  * Capping (outlier control)
  * Smoothing

---

## 📂 Project Structure

```
forecasting-project/
│
├── data/
│   └── Lead_Pricing.csv
│
├── notebooks/
│   └── forecasting.ipynb
│
├── src/
│   ├── recursive.py
│   ├── direct.py
│   ├── hybrid.py
│   ├── mimo.py
│
├── results/
│   └── final_results.txt
│
├── README.md
└── requirements.txt
```

---

## 📈 Final Results

| Model     | MAPE (%) | Accuracy (%) |
| --------- | -------- | ------------ |
| Recursive | 2.39     | 97.61        |
| Hybrid    | 2.95     | 97.05        |
| Direct    | 3.47     | 96.53        |
| MIMO      | 8.73     | 91.27        |

🏆 **Best Model: Recursive**

---

## 🧠 Key Insights

* Recursive models performed best due to strong short-term dependencies
* Hybrid models provided stable long-term predictions
* MIMO struggled due to over-generalization

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn

---

## ▶️ How to Run

1. Clone the repository:

```
git clone https://github.com/YOUR-USERNAME/time-series-forecasting.git
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the notebook or scripts:

```
python src/recursive.py
```

---

## 📌 Future Improvements

* Deep learning models (LSTM, GRU)
* Feature expansion (rolling averages, external factors)
* Automated hyperparameter tuning

---

## 👤 Author

**Vihaan Agarwal**

🔗 LinkedIn: www.linkedin.com/in/vihaan-agarwal-2540512aa

---

## ⭐ If you like this project

Give it a star ⭐ on GitHub!

