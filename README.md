# 📊 Retail Sales Forecasting System (End-to-End ML Web App)

## 📌 Project Overview

This project is an end-to-end Machine Learning web application designed to forecast retail sales based on multiple store and economic factors.

It combines a trained ML model with a Flask backend and an interactive frontend dashboard to deliver real-time sales predictions.

---

## 🎯 Business Objective

Retail businesses need accurate demand forecasting to:
- Optimize inventory management
- Reduce stock shortages and overstocking
- Improve supply chain efficiency
- Make data-driven business decisions

This system predicts weekly sales using historical and external factors.

---

## 🧠 Machine Learning Model

- **Algorithm:** Random Forest Regressor (or trained model used)
- **Task:** Regression (Sales Prediction)
- **Input Features:**
  - Store ID
  - Temperature
  - Fuel Price
  - CPI
  - Unemployment
  - Holiday Flag
  - Date features (Week, Month, Year)

---

## ⚙️ System Architecture

### 🔹 Frontend
- HTML
- CSS (Dark UI Dashboard)
- JavaScript (Fetch API integration)

### 🔹 Backend
- Flask API
- JSON-based communication
- Model inference endpoint (`/predict`)

### 🔹 ML Pipeline
- Feature engineering from date
- Model loading using Joblib
- Real-time prediction processing

---

## 📊 Dashboard Features

- 🔮 Predict weekly sales in real time
- 💰 Display predicted revenue
- 📦 Estimate forecasted units
- ⚠️ Stock-out risk analysis
- 📈 Interactive UI cards for results

---

## 🚀 How It Works

1. User enters store and economic parameters
2. Frontend sends request to Flask API
3. Backend processes input and extracts time features
4. ML model predicts weekly sales
5. Results are displayed dynamically in UI cards

---

## 🛠️ Tech Stack

- Python
- Flask
- Pandas, NumPy
- Scikit-learn
- Joblib
- HTML, CSS, JavaScript

---

## 📁 Project Structure

├── app.py 
├── templates/ 
│   └── index.html 
├── static/ 
│   ├── style.css 
│   └── script.js 
├── random_forest_model.joblib 
└── README.md

---

## 💡 Key Learning Outcomes

- End-to-end ML deployment
- Flask API development
- Frontend-backend integration
- Real-time prediction systems
- Feature engineering from time-series data
- Business-focused ML problem solving

---

## 📌 Future Improvements

- Add model explainability (SHAP values)
- Deploy on cloud (Render / AWS)
- Add database logging for predictions
- Improve UI analytics dashboard

---

## 👤 Author

Developed as a Machine Learning + Full Stack integration project.